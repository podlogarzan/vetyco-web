# Vetyco legal pages (static)

Self-contained HTML for the **public** Privacy Policy + Terms of Service.
Google Play **requires a public Privacy Policy URL** for the store listing.

Files: `index.html`, `privacy.html`, `terms.html` (no build step, no dependencies).

## Easiest free hosting — GitHub Pages
1. Push this repo to GitHub.
2. Repo → Settings → Pages → Source: `Deploy from a branch` → branch `main`, folder `/website`
   (or move these files to `/docs` and pick `/docs`).
3. Your URLs become:
   - `https://<user>.github.io/<repo>/privacy.html`
   - `https://<user>.github.io/<repo>/terms.html`

## Or your own domain (vetyco.app)
Upload the three files to any static host (Netlify drag-and-drop, Vercel, Cloudflare
Pages, or your web host) and use e.g. `https://vetyco.app/privacy.html`.

## Where to paste the URLs
- **Google Play Console** → App content → Privacy policy → the `privacy.html` URL.
- The in-app screens (`src/app/privacy.tsx`, `src/app/terms.tsx`) already mirror this text,
  and the paywall links to them — keep both in sync when you edit.
