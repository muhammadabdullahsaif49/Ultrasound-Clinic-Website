# Iqbal Ultrasound Clinic — Website

Static website for Iqbal Ultrasound, National Diagnostic Complex, Sheikh Zaid Hospital Road, Rahim Yar Khan.

## Pages

- `index.html` — Home
- `about.html` — About / team
- `services.html` — Services overview
- `contact.html` — Contact & appointment form
- `services/` — Individual service detail pages:
  - `obstetric.html` — Obstetric & Pregnancy
  - `abdominal.html` — Abdominal & Pelvic
  - `cardiac.html` — Cardiac (Echo)
  - `doppler.html` — Doppler & Vascular
  - `thyroid.html` — Thyroid & Small Parts
  - `msk.html` — Musculoskeletal
  - `pediatric.html` — Pediatric Ultrasound
  - `prostate.html` — Prostate (TRUS)
  - `elastography.html` — Elastography
  - `health-screening.html` — Health Screening Packages
  - `css/styles.css`
  - `js/main.js`

Add these under `css/` and `js/` folders at the repo root to match the relative paths already used in the HTML (root pages use `css/styles.css`, service pages use `../css/styles.css`).

## Deploying

This is a plain static site — no build step. It can be served as-is via GitHub Pages, Netlify, Vercel, or any static host.

### GitHub Pages quick start

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin <your-repo-url>
git push -u origin main
```

Then enable GitHub Pages in the repo settings (Settings → Pages → Deploy from branch → `main` → `/root`).
