# alethic-labs.com

The website for [Alethic](https://github.com/shubhambaid/alethic): one static page, served by GitHub Pages at [alethic-labs.com](https://alethic-labs.com). There is no build step.

| File | Purpose |
|---|---|
| `index.html` | The page, with its styles and a few lines of script inline. Fonts (Bodoni Moda, IBM Plex Sans, JetBrains Mono) load from Google Fonts. |
| `assets/dashboard-walkthrough.mp4`, `assets/dashboard-walkthrough-poster.jpg` | A one-minute recording of `alethic dashboard` on the demo repository (1920×1080, H.264) and its poster frame |
| `assets/dashboard.webp`, `assets/dashboard.png` | Dashboard screenshot (WebP, with a PNG fallback and social preview) |
| `favicon.svg` | Site icon |
| `CNAME` | Custom domain for GitHub Pages |

Preview locally with `python3 -m http.server` and open http://localhost:8000.

To refresh the screenshot, copy `docs/assets/dashboard.png` from the Alethic repository, resize it to 2000 px wide, and export a WebP next to it.
