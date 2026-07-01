# INFLUENZERS — Static Site

Self-contained static build. All HTML, JS, CSS, fonts, images, and the favicon are bundled. No server or env vars required.

## Deploy to GitHub Pages
1. Create a new GitHub repo.
2. Copy the contents of this folder to the repo root (or into `docs/`).
3. Push.
4. Settings → Pages → Source: Deploy from a branch → pick branch and `/ (root)` or `/docs`.
5. Site publishes at `https://<user>.github.io/<repo>/`.

`404.html` is included as an SPA fallback so `/terms-of-service`, `/privacy-policy`, and `/creator-terms` work on refresh.

## Deploy anywhere else
Upload the folder contents to any static host — Netlify, Vercel, Cloudflare Pages, S3 + CloudFront, Nginx. If the host does not auto-serve `404.html` for unknown paths, configure a SPA fallback rewriting unknown paths to `/index.html`.

## Notes
- Language auto-detects (Arabic / English) and persists in `localStorage`.
- All external links open in new tabs.
