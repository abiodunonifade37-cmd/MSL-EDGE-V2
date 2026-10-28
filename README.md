# MSL Edge Flow V2.0

A mobile-first, dark-theme liquidity-trading practice PWA. The package is organized into separate HTML, CSS and JavaScript files and includes offline app-shell caching.

## Files
- `index.html` — application structure
- `styles.css` — responsive dark UI
- `app.js` — app interactions and local workspace logic
- `manifest.webmanifest` — installable PWA metadata
- `sw.js` — service worker for offline app-shell caching
- `icon.svg` — app icon

## Run it
For the simplest reliable setup, publish the **contents** of this folder to the root of a GitHub Pages repository, or serve the folder using a local web server. Service workers and install prompts require HTTPS or localhost; opening `index.html` directly as a file will not enable all PWA behavior.

## Important limitations
- The practice chart/candles are simulated for learning and chart-marking practice. This package does not connect to a live market-data feed or broker and does not place orders.
- Journal data is stored in this browser on this device. Use the built-in export/backup feature regularly; local data does not automatically sync between devices.
- Notification permission does not guarantee delivery when the browser or app is suspended or closed. Reliable scheduled background notifications require a supported push-notification backend and platform permissions.
- Risk and R-multiple calculations are educational estimates. Confirm contract specifications, tick values and broker rules before using any position-size figure in a live account.

## Deploy to GitHub Pages
1. Extract the ZIP.
2. Open the `MSL_EDGE_FLOW_V2` folder.
3. Upload all files and the `assets` folder if present to the repository root (these files use the root `icon.svg`).
4. In GitHub, open **Settings → Pages**, select the deployment branch and root folder, then save.
5. Open the published site over HTTPS. On mobile, use the browser menu's **Add to Home screen** / **Install app** option if available.

This is a deployable PWA project package, not a site already published to a public URL.
