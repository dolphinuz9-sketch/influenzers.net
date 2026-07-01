# Deploy to Vercel

Use this folder as a pre-built static site.

## Steps
1. Unzip `influenzers-static-site.zip`.
2. Upload or import the unzipped folder contents to Vercel.
3. Select **Other** as the framework and leave the build command empty.

Do not upload the parent source project unless you want Vercel to run a fresh build. This export is already built and ready.

## White screen prevention
- Asset paths are relative: `./assets/...`.
- Routing uses `#/page`, so internal pages do not require server routing.
- `vercel.json` disables builds and provides a fallback to `index.html`.
