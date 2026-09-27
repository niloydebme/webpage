---
permalink: /
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div class="prose">
<p class="greeting">Greetings and welcome!</p>

<p>I am <strong>Niloy Deb</strong> (/ˈniː.loɪ dɛb/), currently a lecturer in the Department of Petroleum and Mineral Resources Engineering (PMRE) at Bangladesh University of Engineering and Technology (BUET), Dhaka. Before joining there, I worked as a research assistant in the Computational Fluid Dynamics and Heat Transfer (CFDHT) Research Group, led by Dr. Sumon Saha (Professor, Department of Mechanical Engineering, BUET). I completed my B.Sc. in Mechanical Engineering from BUET and am a prospective doctoral student in Mechanical Engineering, starting in Fall 2027.</p>

<p>My research interests include chaotic dynamical (fluid) systems, physics of convection, and turbulence. Many of my completed or ongoing research projects are related to CFD-based fluid system control, fluid flow through porous and subsurface media, and fluid behavior in multiphysics environments (constraints). My current focus is on integrating numerical analysis and high-fidelity (multiscale) computational fluid dynamics (CFD) with data-driven and differentiable physics methods to improve predictive accuracy, computational efficiency, and understanding of engineering systems. This requires modeling and prediction through scientific machine learning (SciML), as well as optimizing complex nonlinear phenomena using adjoint methods, Bayesian statistics, and gradient-based or metaheuristic algorithms. Above all, it entails combining knowledge from statistical inference, machine learning (ML), and deep learning (DL) with physics-based modeling.</p>
</div>

<section class="news">
  <h2>News &amp; Updates</h2>
  {% comment %}Newest first. The latest 10 show; older items are under "See all". Edit _data/news.yml.{% endcomment %}
  {% assign news = site.data.news | sort: "date" | reverse %}
  <ul>
    {% for item in news limit: 10 %}
    <li><div><span class="news-date">{{ item.date }}</span><span>{{ item.text }}</span></div></li>
    {% endfor %}
  </ul>
  {% if news.size > 10 %}
  <details class="news-more">
    <summary>See all ({{ news.size }})</summary>
    <ul>
      {% for item in news offset: 10 %}
      <li><div><span class="news-date">{{ item.date }}</span><span>{{ item.text }}</span></div></li>
      {% endfor %}
    </ul>
  </details>
  {% endif %}
</section>
