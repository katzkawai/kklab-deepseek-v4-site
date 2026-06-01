# kklab-deepseek-v4-site

**Single-file static landing page.** No build tools, no package manager, no JS framework.

## Structure

- `index.html` — entire site (HTML + inline CSS, zero JavaScript)

## Develop

Serve locally with any HTTP server:

```sh
python3 -m http.server 8000
```

No install, lint, typecheck, or test commands exist.

## Deploy

Push to `main` — GitHub Pages auto-deploys from the default branch.

URL: https://katzkawai.github.io/kklab-deepseek-v4-site/

## Content notes

- All content is in Japanese (`lang="ja"`).
- External resources: Unsplash hotlinked images, Google Maps embed iframe.
- No SEO/OG tags, no favicon, no accessibility attributes.
