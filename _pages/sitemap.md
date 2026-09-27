---
published: false   # kept for internal use; not built or shown on the site
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

<p>A list of all the posts and pages found on the site. For you robots out there is an <a href="{{ '/sitemap.xml' | relative_url }}">XML version</a> available for digesting as well.</p>

<h2>Pages</h2>
<ul>
  {% for link in site.data.navigation.main %}<li><a href="{{ link.url | relative_url }}">{{ link.title }}</a></li>
  {% endfor %}
</ul>

<h2>Publications</h2>
<ul>
  {% assign pubs = site.publications | sort: "date" | reverse %}
  {% for pub in pubs %}<li><a href="{{ pub.url | relative_url }}">{{ pub.title }}</a></li>
  {% endfor %}
</ul>

<h2>Teaching</h2>
<ul>
  {% for doc in site.teaching reversed %}<li><a href="{{ doc.url | relative_url }}">{{ doc.title }}</a></li>
  {% endfor %}
</ul>
