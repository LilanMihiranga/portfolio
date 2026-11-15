# Lilan Jayasuriya – Portfolio

Personal portfolio site. Plain HTML and CSS, no build step.

## Files

- `index.html` – all page content
- `styles.css` – styling
- `vercel.json` – security headers and clean URLs for Vercel

## Edit locally

Open `index.html` in a browser, or run a local server:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy

The site is deployed on Vercel from this repo:

- Push to `main` → production deployment
- Open a pull request → preview deployment with its own URL

Vercel settings: Framework Preset **Other**, no build command, output directory `.` (root).
