# Cyber Polygon — Project Website

Static website for **Cyber Polygon: A Cyber Range Platform Specialized on Energy Sector with Automatic Generation of Virtual Scenarios**, a NATO Science for Peace and Security project developed by ICI Bucharest (Romania) and SCIS Azerbaijan.

## Stack

Plain HTML, CSS, and vanilla JavaScript — no build step, no dependencies.

```
index.html            # single-page site
css/style.css         # design system + layout
js/main.js            # mobile nav, scroll reveal, active-section highlighting
img/                  # partner logos and NATO SPS banner
.github/workflows/    # GitHub Pages deployment
```

## Local preview

Any static server works, e.g.:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deployment

The site deploys automatically to **GitHub Pages** via GitHub Actions on every push to `main` (see `.github/workflows/deploy.yml`).

One-time setup after pushing the repository to GitHub:

1. Open the repository **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. Push to `main` (or run the workflow manually from the Actions tab).
