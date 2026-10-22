# lkurlandski.github.io

Personal research website of Luke Kurlandski, built on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template and deployed to GitHub Pages by `.github/workflows/jekyll.yml` on every push to `master`.

## Where things live

| What | File |
| --- | --- |
| Name, sidebar links, avatar | `_config.yml` (`author:` block) |
| Home page (bio, news, selected papers) | `_pages/about.md` |
| Research page | `_pages/research.md` |
| Publications (one file each) | `_publications/*.md` |
| Publication categories and order | `_config.yml` (`publication_category:`) |
| Top navigation | `_data/navigation.yml` |
| CV | `files/cv.pdf` |
| Site-specific styles | `_sass/layout/_custom.scss` |

To feature a paper on the home page, add `selected: true` to its front matter. Optional link fields: `paperurl`, `slidesurl`, `videourl`, `codeurl`, `pageurl`, `bibtex`.

## Local preview

```bash
bundle install
bundle exec jekyll serve -l -H localhost   # http://localhost:4000
```
