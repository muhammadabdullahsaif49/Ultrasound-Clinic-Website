# Iqbal Ultrasound Clinic — Website

Static website for Iqbal Ultrasound, National Diagnostic Complex, Sheikh Zaid Hospital Road, Rahim Yar Khan.

## Pages

- `index.html` — Home
- `about.html` — About / team
- `services.html` — Services overview
- `contact.html` — Contact & appointment form

## Required but missing assets

These pages reference the following files, which were **not** included in this upload and must be added before the site will render/style correctly:

- `css/styles.css`
- `js/main.js`

Also linked (but not yet created) from the nav/footer/category cards:

- `services/obstetric.html`
- `services/abdominal.html`
- `services/cardiac.html`
- `services/doppler.html`
- `services/thyroid.html`
- `services/msk.html`
- `services/pediatric.html`
- `services/prostate.html`
- `services/elastography.html`
- `services/health-screening.html`

Add these under a `css/`, `js/`, and `services/` folder at the repo root respectively to match the relative paths already used in the HTML.

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
