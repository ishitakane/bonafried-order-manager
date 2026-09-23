# BonaFried — GitHub Pages

This folder is ready to upload to a GitHub repository and publish with GitHub Pages.

## Files

- `index.html` — BonaFried Order Manager
- `manifest.json` — makes the site installable as a PWA
- `sw.js` — caches the app shell for offline use
- `icon-192.png` — app icon
- `icon-512.png` — app icon

## Publish on GitHub

1. Create a new GitHub repository, for example `bonafried-order-manager`.
2. Upload **all five files** from this folder.
3. Make sure `index.html` is in the repository root.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ (root)**
6. Click **Save**.
7. Wait for GitHub Pages to deploy.
8. Open:
   `https://YOUR-USERNAME.github.io/bonafried-order-manager/`

## On your phone

Open the GitHub Pages URL in your phone browser.

- iPhone/Safari: Share → **Add to Home Screen**
- Android/Chrome: menu → **Add to Home screen** / **Install app**

## Important

The order data is stored locally in the browser/device using the app's existing IndexedDB/localStorage system. GitHub Pages hosts the app itself; it does **not** automatically sync orders between phones or computers.

Use the app's backup/export feature regularly so your order data is not lost if browser storage is cleared.
