# Niloy Deb: academic website

Live at **https://niloydebme.github.io/webpage/**. Built with Jekyll on the [AcademicPages](https://github.com/academicpages/academicpages.github.io) / Minimal Mistakes theme and published by GitHub Pages from this repository.

## Where to edit what

| To change | Edit |
|---|---|
| Name, sidebar bio, e-mail, profile links, site description | `_config.yml` → `author:` |
| Header menu | `_data/navigation.yml` |
| Home page intro and research-interests diagram | `_pages/about.md` |
| Home page **News & Updates** | `_data/news.yml` (newest first) |
| Research page | `_pages/research.html` |
| CV page | `_pages/cv.html` (publications fill in automatically) |
| Publications | one file per paper in `_publications/` (see below) |
| Teaching list / course pages | `_pages/teaching.html` / `_teaching/*.md` |
| Blog / Webliography | `_pages/year-archive.html` |
| Page frame (header, tabs, footer) | `_layouts/minimal.html`; header lines and CV link in `_config.yml` -> `author:` |
| Colours, fonts, spacing | `assets/css/site.css` |
| Images / downloadable files | `images/`, `files/` |

Pages use CSS classes defined in `assets/css/site.css` rather than inline `style="..."` attributes, so a look change is made in one place.

### Adding a news item

Add at the top of `_data/news.yml`:

```yaml
- date: 2026-10-01
  text: "Short description. <b>Bold</b> and <a href='https://...'>links</a> are allowed."
```

### Adding a publication

Create `_publications/YYYY-journal-firstauthor.md` (lower-case, hyphens, no spaces):

```yaml
---
title: "Paper title in sentence case"
authors: "A. Author, Niloy Deb, B. Author"
venue: "Journal Name"            # or "Proc. <Conference name> (<ACRONYM YEAR>)"
details: "Vol. 12, Article 3456" # volume/pages; optional
year: 2026
doi: "10.xxxx/xxxxx"             # without https://doi.org/
pdf: "/files/paper.pdf"          # optional, file in files/
note: "Best Paper Award"         # optional
category: manuscripts            # manuscripts | conferences | books
date: 2026-01-31                 # used for ordering
keywords: "Keyword | Keyword | Keyword"
---

Abstract text as one plain paragraph.
```

It then appears, formatted identically, on the Publications page and in the CV (grouped by category, newest first), and gets its own abstract page. "Niloy Deb" is bolded automatically.

### Linking an image or file

Always go through `relative_url` so the `/webpage` prefix is added for you:

```html
<img src="{{ '/images/figure.png' | relative_url }}" alt="…">
<a href="{{ '/files/lecture.pdf' | relative_url }}">[pdf]</a>
```

Use lower-case file names without spaces.

## Deploying

Commit and push to the branch GitHub Pages builds from (Settings → Pages; currently `master`). GitHub builds the site in a minute or two; build errors appear under the repository's **Actions** tab.

## Previewing locally (optional)

Requires Ruby 3.x with Bundler ([RubyInstaller](https://rubyinstaller.org/) on Windows, with the MSYS2 dev kit).

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000/webpage/. Restart the server after editing `_config.yml`.

## License

Theme code is MIT-licensed (see `LICENSE`); site content © Niloy Deb.
