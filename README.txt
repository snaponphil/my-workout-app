MY WORKOUT — 12-WEEK IPHONE PWA PROTOTYPE

FILES
index.html, style.css, app.js, manifest.webmanifest, sw.js, icon.svg

TRY IT ON A COMPUTER
Run a local HTTP server from this folder, e.g. python3 -m http.server 8000
Then open http://localhost:8000 in a browser.

INSTALL ON IPHONE
1. Upload the contents of this folder to a static HTTPS hosting service (e.g. GitHub Pages, Netlify, Cloudflare Pages).
2. Open the HTTPS URL in Safari on your iPhone.
3. Tap Share > Add to Home Screen.
4. Launch from the new icon. After the first online load, cached assets work offline.

DATA
Stored only in localStorage on the device/browser. No login or cloud synchronization.
Use Settings > Export full backup regularly and save JSON in iCloud Drive or Files.
CSV exports logged sets for spreadsheet analysis. JSON backup restores app data.

NOTES
The app is a functional prototype; it has not been published or deployed to a hosting provider.
A few movements such as treadmill intervals are logged using numeric reps as a flexible placeholder.
If you open index.html directly as a file, service worker installation/offline mode won't work.
