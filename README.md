# Open PoL

Public website for **Open PoL**: a short public home for open Proof-of-Location ideas, verifiable claims of place and time, and capture-time provenance.

The site is intentionally minimal and static. It is served directly from the repository root through GitHub Pages.

## Site

Expected GitHub Pages URL:

```text
https://open-pol.github.io
```

## Structure

```text
.
├── index.html
├── styles.css
├── assets/
│   ├── favicon.svg
│   └── open-pol-hero.png
└── .github/workflows/pages.yml
```

## Local Preview

Open `index.html` directly in a browser, or serve the repository root with any static file server:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Deployment

GitHub Pages is deployed by `.github/workflows/pages.yml` on every push to `main`.

In the GitHub repository settings, configure:

- `Settings` -> `Pages`
- `Build and deployment`
- `Source`: `GitHub Actions`
