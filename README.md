# prasenjit52282.github.io

Personal academic site for Prasenjit Karmakar. The entire site is a single
self-contained file: **`index.html`** (HTML, CSS and JS all inline). There is
no build step, no framework, and no static site generator — just edit the
file and push.

## Editing

Open `index.html` in any editor. Content is organized into clearly
labeled `<section>` blocks (About, Experience, Publications, Open Source,
News, Contact) — find the section you want to change and edit the markup
directly. Images live under `img/` and the CV under `files/`.

## Preview locally

Any static file server works, e.g.:

```
python3 -m http.server 8000
```

then open http://localhost:8000/.

## Deploy

Pushing to `main` triggers `.github/workflows/deploy.yml`, which publishes
the repository root to GitHub Pages — no build step involved.
