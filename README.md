# INFLUENZERS — Static Site

This folder is a complete static export. Upload the folder contents as-is. No server, environment variables, or build step are required.

## Required files included
- `index.html`
- `404.html`
- `favicon.png`
- `robots.txt`
- `assets/`
- `vercel.json`

## Deploy to Vercel

### Best option
1. Unzip `influenzers-static-site.zip`.
2. Open the unzipped folder.
3. Deploy the contents of this folder to Vercel.

Framework Preset: **Other**  
Build Command: leave empty  
Output Directory: `.`

`vercel.json` already tells Vercel not to build and includes the fallback rule.

## Deploy anywhere else
Upload the folder contents to any static host: Netlify, Cloudflare Pages, GitHub Pages, S3, Nginx, cPanel, or similar.

The site uses relative asset paths and hash-based routing, so it keeps working even if hosted inside a subfolder.
