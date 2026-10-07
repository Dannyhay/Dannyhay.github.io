# dannyhay.github.io

Personal academic website of **Daniel Fiifi Tawia Hagan** — Hydro-Climate Extremes Lab (H-CEL),
Ghent University. Built with [Jekyll](https://jekyllrb.com/) and the
[Contrast](https://github.com/niklasbuschmann/contrast) theme, served by GitHub Pages at
<https://dannyhay.github.io>.

## Editing the site

Each page is a single Markdown file at the root. Edit it on github.com (pencil icon) or locally and
push — GitHub rebuilds and republishes within about a minute. There is no build step to run yourself.

| Page | File |
| --- | --- |
| About me (home) | `index.md` |
| News | `news.md` |
| Research & Projects | `research.md` |
| Publications | `publications.md` |
| Talks & Outreach | `talks.md` |
| Teaching & Supervision | `teaching.md` |
| Data & Tools | `tools.md` |
| Social Life | `social.md` |
| CV | `cv.md` |

Common edits:

- **A news item** — copy one `<li> … </li>` block at the top of `news.md`, change the date and text.
- **A publication** — copy one `<li>` line in `publications.md` under the right year.
- **A picture** — put the file in `figure/` and reference it as
  `{{ '/figure/name.jpg' | relative_url }}`. Keep images under ~1 MB.
- **A menu item** — add the file to `navigation:` in `_config.yml`.
- **Footer links** — `external:` in `_config.yml`.
- **The CV PDF** — replace `assets/Daniel_Hagan_CV.pdf`.

Styling lives in `_sass/custom.sass` (the theme's own styles are in the other `_sass` files). The
accent colour is `$link-color` in `_sass/index.sass`.

## Preview locally (optional)

With Ruby installed:

```bash
bundle install
bundle exec jekyll serve
```

then open <http://localhost:4000>. GitHub Pages builds the site for you, so this is never required.

## Licence

Theme: public domain (see `UNLICENSE.txt`). Content © Daniel Fiifi Tawia Hagan.
