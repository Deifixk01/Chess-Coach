# Chess Coach

Play chess against the computer while a coach suggests moves and explains why they're good.
Everything runs in your browser — no server, no tracking, works offline once loaded.

## Host it on GitHub Pages

1. Create a new **public** repository on github.com (for example `chess-coach`).
2. **Add file → Upload files**, and upload every file from this folder
   (`index.html`, `sw.js`, `manifest.webmanifest`, `apple-touch-icon.png`, `icon-192.png`, `icon-512.png`, `README.md`). Commit.
3. Go to **Settings → Pages**. Under *Build and deployment*, set Source to **Deploy from a branch**,
   choose branch **main** and folder **/ (root)**, then **Save**.
4. After a minute or two your app is live at `https://YOUR-USERNAME.github.io/chess-coach/`.

## Add it to your iPhone home screen

1. Open the URL above in **Safari**.
2. Tap the **Share** button → **Add to Home Screen** → **Add**.
3. Launch it from the icon — it opens full-screen like a regular app and works offline.

## Updating

Upload a new `index.html` to the repo. The app picks up the new version the next time it's opened online.
If you change cached files often, bump `CACHE` in `sw.js` (e.g. `chess-coach-v2`).
