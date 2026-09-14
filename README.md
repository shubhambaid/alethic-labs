# alethic-labs.com

The website for [Alethic](https://github.com/shubhambaid/alethic): one static page, served by GitHub Pages at [alethic-labs.com](https://alethic-labs.com). There is no build step.

| File | Purpose |
|---|---|
| `index.html` | The page, with its styles and a few lines of script inline |
| `assets/dashboard.webp`, `assets/dashboard.png` | Dashboard screenshot (WebP, with a PNG fallback and social preview) |
| `favicon.svg` | Site icon |
| `CNAME` | Custom domain for GitHub Pages |

Preview locally with `python3 -m http.server` and open http://localhost:8000.

To refresh the screenshot, copy `docs/assets/dashboard.png` from the Alethic repository, resize it to 2000 px wide, and export a WebP next to it.
