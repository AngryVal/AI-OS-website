# CEO AI OS — website

Single-page site for the CEO AI OS, a Three Tomorrows productised service. Built as a static site (`index.html` + `styles.css`) so it can be hosted on GitHub Pages with no build step.

## Local preview

Just open `index.html` in a browser, or run any static server in this folder:

```
python3 -m http.server 8000
# then open http://localhost:8000
```

## Files

- `index.html` — markup and content
- `styles.css` — all styling (Three Tomorrows brand: charcoal/off-white, mint accent)

## Brand

Follows the Three Tomorrows brand guidelines:

- **3T Charcoal** `#191C1C` (primary type, ink)
- **Off White** `#FBFCFD` (paper ground)
- **3T Mint Green** `#3BE494` (single accent)
- Editorial typography pairing — Source Serif 4 (display) + Inter (UI/body) + IBM Plex Mono (kickers, numerics). All loaded from Google Fonts.

## Editing copy

All site copy lives directly in `index.html`. To update:

1. Edit the relevant section in `index.html`
2. Commit and push — GitHub Pages will redeploy automatically

## Deployment

Hosted on GitHub Pages from the `main` branch root.
