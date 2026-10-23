# urgencia.ssonydental.com

Spanish urgent care dental landing page for Smile Services of New York.

## Deploy with GitHub Pages
1. Create a new repo (e.g. `ssonydental/ssny-urgencia`) and upload every file in this folder to the root (keep the `assets/` folder and `.nojekyll`).
2. Settings > Pages > Source: Deploy from a branch > `main` / `/ (root)` > Save.
3. In your DNS, add a CNAME record: `urgencia` -> `ssonydental.github.io`.
4. Settings > Pages > Custom domain: `urgencia.ssonydental.com`, then tick Enforce HTTPS once the certificate is issued.

The `CNAME` file keeps the custom domain set across deploys.

## Language linking (hreflang)
This page declares the English version at https://urgent.ssonydental.com/. Add the same three `<link rel="alternate" hreflang>` tags to the English page's <head> so Google pairs them.

## Still to fill in (search index.html for "fill in")
- Privacy Policy URL
- Google Business Profile URL (sameAs)
- Optional photos: assets/exterior.jpg, assets/interior.jpg (cards hide themselves if missing)
