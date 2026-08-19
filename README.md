# Cabot Crime and Flock Analysis

A mobile-first, source-linked public report comparing Cabot, Arkansas crime before and during the city's use of Flock Safety automated license-plate readers.

## Files

- `index.html` — complete report
- `styles.css` — responsive and print styles
- `app.js` — data tables and share/print behavior
- `og-image.png` — Facebook/Open Graph preview (1200×630)
- `og-image.svg` — editable source for the preview graphic

## Preview locally

```bash
python3 -m http.server 8080
```

Then open <http://localhost:8080>.

## Publishing

The site has no build step or external runtime dependencies and can be published from the repository root on GitHub Pages, Cloudflare Pages, Netlify, or any static host.

The Open Graph metadata uses the expected GitHub Pages URL. Change `og:url`, `og:image`, and `link rel="canonical"` in `index.html` if publishing elsewhere.

## Editorial scope

- Pre-Flock period: 2016–2021
- Transition year excluded from averages: 2022
- During-Flock period: 2023–2025
- January–June 2026 is presented separately as preliminary data
- The August 2026 suspension cannot yet be evaluated as a post-Flock period

The report describes associations in public data and does not claim causal effects.