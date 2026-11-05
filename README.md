# Photo Monogram Press

Turn a photo into an engraved, single-ink monogram with your initials. Runs entirely in the browser: photos never leave your device.

## Features
- Take a photo (phone camera) or upload / drag-and-drop an image
- Frames: Seal, Crest, Lozenge, Cartouche
- Engraving styles: line engraving, halftone, stencil
- Exposure, contrast, density and zoom controls
- Five ink colors
- Download a 1200×1200 PNG

## Publish on GitHub Pages
1. Create a new repository on GitHub (e.g. `photo-monogram-press`).
2. Upload `index.html`, `README.md` and `.nojekyll` to the repo root (or push with git, below).
3. Go to **Settings → Pages**, set **Source** to *Deploy from a branch*, branch `main`, folder `/ (root)`.
4. After a minute the site is live at `https://<username>.github.io/photo-monogram-press/`.

```bash
git init -b main
git add .
git commit -m "Photo Monogram Press"
git remote add origin https://github.com/<username>/photo-monogram-press.git
git push -u origin main
```

No build step and no dependencies besides Google Fonts.
