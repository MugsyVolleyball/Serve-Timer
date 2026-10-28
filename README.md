# Volleyball Serve Timer

Times volleyball serves and keeps a log for each player and each game. Works offline once installed.

## Put it on GitHub Pages
1. Sign in at github.com and create a **New repository** (for example `serve-timer`). Set it to Public.
2. Click **Add file > Upload files** and drag in all five files: `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png` and `icon-512.png`. Keep them all in the top level, with no folders. Click **Commit changes**.
3. Go to **Settings > Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, pick the `main` branch and the `/ (root)` folder, then **Save**.
4. After a minute or two the page shows your address: `https://YOUR-USERNAME.github.io/serve-timer/`

## Install on your phone
- **iPhone:** open the address in Safari, tap Share, then **Add to Home Screen**.
- **Android:** open it in Chrome, tap the menu, then **Install app** (or **Add to Home screen**).

Open it once with signal so it can save itself for offline use.

## Good to know
- Serves are saved on the phone itself and don't sync between devices. Use **Export CSV** after each session.
- Data entered in Safari and data in the home-screen icon can be kept separately on iPhone. Pick one and stick with it.
- If you edit `index.html` later, change `serve-timer-v1` to `serve-timer-v2` in `sw.js` so phones pick up the update.
