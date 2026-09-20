# C&J Commercial Construction — website source

Static marketing site for cjcommercialconstruction.com, exported from its Cloudflare Pages
deployment (project `cj-commercial-construction`, no Git repo was previously connected — this
was a direct-upload deployment, so this export *is* the source).

## Structure

- `index.html` — page markup
- `styles.css` — all styles
- `script.js` — mobile nav, scroll reveals, animated stats, and the contact form (opens the
  visitor's email client addressed to CoryGardner@cjcommercialconstruction.com)
- `assets/` — logo images (see note below)

## Note on image assets

Two images were deployed alongside the code but could not be exported automatically:

- `assets/logo-header.png` — https://cjcommercialconstruction.com/assets/logo-header.png
- `assets/logo.png` — https://cjcommercialconstruction.com/assets/logo.png

Download those two files from the URLs above and place them in `assets/` before deploying
elsewhere (e.g. GitHub Pages, Netlify, Vercel) — the HTML already references them at those paths.

## Deploying

This is a plain static site (no build step, no framework, no dependencies) — any static host
will serve it as-is.
