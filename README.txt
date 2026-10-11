FUELDESK PROFESSIONAL - LAUNCH PACKAGE

FILES
- index.html: public landing page with Open and Download buttons
- app.html: hosted app with a service worker registration and PWA manifest link
- FuelDesk-Professional-Offline.html: downloadable standalone HTML copy
- manifest.webmanifest, service-worker.js, icon.svg: install/offline support for the hosted app

HOSTING
1. Upload the CONTENTS of this folder to a static website host that serves HTML, JS, SVG, and .webmanifest files over HTTPS.
2. Keep all files in the same root folder; do not rename app.html, service-worker.js, manifest.webmanifest, or icon.svg.
3. Visit the public site URL, open app.html once, then reload it. If the browser offers Install app/Add to Home Screen, use it.
4. Test airplane mode/offline after the first online load, then test sales, backup, restore, and printing with SAMPLE DATA.
5. Keep a local copy of this package and version it before every release.

IMPORTANT LIMITS
- This package is static hosting only. It does not provide customer accounts, payments, remote monitoring, cloud backups, or automatic data sync.
- Records are stored locally in the browser origin on each device. Different devices and browsers have separate data. Clearing browser data can erase records.
- The hosted app should be accessed at the same permanent URL. Do not switch customers between hosted and file:// versions without exporting/importing a backup.
- The standalone HTML copy may have browser-specific local storage and offline behavior; verify on the customer's actual device.
- Service worker offline caching requires HTTPS (or localhost) and a compatible browser. After first load, reload once and test offline before relying on it.
- Demo PINs are basic protection only. Change them and do not claim enterprise-grade security.
- This is a pilot package; thoroughly test with sample data before live commercial operations.
