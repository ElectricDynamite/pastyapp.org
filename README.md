# pastyapp.org

Source for [www.pastyapp.org](https://www.pastyapp.org), the website of Pasty Cloud Clipboard. Built with [Hugo](https://gohugo.io), no theme.

## Local preview

```bash
hugo server
```

Then open http://localhost:1313.

## Layout

- `content/` – pages (FAQ entries and APK list live in the frontmatter of `faq.md` and `download.md`)
- `layouts/` – templates and partials
- `static/` – CSS, images, JS and the APK files

## Deployment

Every push to `main` builds the site and deploys it to GitHub Pages via `.github/workflows/hugo.yml`. The Hugo version is set in `HUGO_VERSION` there.
