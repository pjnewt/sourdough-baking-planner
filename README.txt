# Sourdough Baking Planner — offline PWA

## Install it
A Progressive Web App must be served from HTTPS (or localhost) for browser installation and offline caching. Opening `index.html` directly from a file manager will not enable installation/offline mode.

1. Upload the contents of this folder to a static HTTPS host (for example, your own website or a static hosting service).
2. Open the resulting HTTPS URL in Chrome.
3. Choose **Install app** from Chrome's menu or use the install prompt if offered.
4. Open the installed app once while online. It will then cache its app files for offline use.

## Data and timers
- Recipe ingredients, stage durations, target time and completed stages are saved locally in the browser on that device.
- The app does not send your recipe data to a server.
- Keep the app open for the most reliable countdown updates. Browser/OS power-saving can delay timer updates when the app is backgrounded.
- The schedule uses the durations entered by the baker; it does not automatically predict fermentation from dough temperature.

## Files
- `index.html` — app
- `manifest.webmanifest` — install metadata
- `sw.js` — offline cache service worker
- `icons/` — app icons
