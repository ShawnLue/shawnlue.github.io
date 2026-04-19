# shawnlue.github.io

Personal academic homepage of **Xiangyu Liu (刘翔宇)**, Senior Researcher at WeChat AI, Tencent.

Live at: <https://shawnlue.github.io>

## Structure

```
_config.yml            Site settings
_data/navigation.yml   Top navigation
_data/ui-text.yml      UI strings (theme)
_pages/
  about.md             Home page   (/)
  publications.md      Publications (/publications/)
  cv.md                CV          (/cv/)
  404.md               Not-found page
_publications/         Publication collection (one .md per paper)
_includes/, _layouts/  Jekyll template partials (Minimal Mistakes fork)
_sass/                 Theme SCSS, incl. _custom.scss for overrides
assets/                CSS, JS, fonts
images/                Images
files/                 PDFs / slides
```

## Add a new publication

Create a new markdown file under `_publications/`, e.g. `2026-XYZ-MyPaper.md`:

```yaml
---
title: "Paper Title"
collection: publications
permalink: /publications/MyPaper
excerpt: "One-line summary"
date: 2026-08-01
venue: "KDD"
year: 2026
paperurl: "https://arxiv.org/abs/xxxx.xxxxx"
slide: ""
authorlist: "Author A, Xiangyu Liu, Author B"
citation: "Full citation..."
status: 'pub'   # 'pub' | 'acc' | anything else = Work in progress
---
**Abstract:** ...
```

It will automatically appear on `/publications/` (grouped by year) and on the CV page.
To feature it on the home page, add its permalink key to the `selected_keys` list in `_pages/about.md`.

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.

## Deployment

Commit to `master`. GitHub Pages builds and deploys automatically.

## Credits

Forked from [AcademicPages](https://github.com/academicpages/academicpages.github.io),
which is itself a fork of [Minimal Mistakes](https://mademistakes.com/work/minimal-mistakes-jekyll-theme/).
