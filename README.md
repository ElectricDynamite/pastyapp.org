# pastyapp.org

Source for [pastyapp.org](https://pastyapp.org), the website of Pasty Cloud Clipboard. Built with [Hugo](https://gohugo.io), no theme.

## Local preview

```bash
hugo server
```

Then open http://localhost:1313.

## Layout

- `content/` – pages (FAQ entries live in the frontmatter of `faq.md`)
- `layouts/` – templates and partials
- `static/` – CSS, images and JS

## Deployment

Every push to `main` builds the site and deploys it to GitHub Pages via `.github/workflows/hugo.yml`. The Hugo version is set in `HUGO_VERSION` there.
