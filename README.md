# Codeward Security — Website

Bilingual (EN/FR) marketing site for Codeward Security — a developer-first cybersecurity firm securing fintech, neo-banks, and financial institutions across North America, Europe & Africa.

**Tagline:** Where Code Meets Conviction.

## About

Single-page static site built with plain HTML, CSS, and JavaScript (no build step, no dependencies). Includes a live English/French language toggle and covers the firm's service portfolio, regional footprint, and positioning.

## Structure

- `index.html` — the entire site (markup, styles, and the EN/FR copy + toggle script)

## Running locally

No build step required. Open `index.html` directly in a browser, or serve it locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

Static-hosting ready as-is (GitHub Pages, Netlify, Vercel, S3, etc.) — just point your host at `index.html`.
