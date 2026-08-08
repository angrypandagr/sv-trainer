SV Trainer PWA

FILES
- index.html
- manifest.webmanifest
- sw.js
- icon-192.png
- icon-512.png
- apple-touch-icon.png

DEPLOY
Upload ALL files together to the same HTTPS folder/root.
Works on GitHub Pages, Cloudflare Pages, Netlify, Vercel, or any normal HTTPS host.

IPHONE INSTALL
1. Open the HTTPS URL in Safari.
2. Tap Share.
3. Tap "Add to Home Screen" / "Προσθήκη στην οθόνη αφετηρίας".
4. Open SV Trainer from the new icon.
5. After the first successful load, the trainer can work offline.

IMPORTANT
Service workers do not run from local file:// URLs. The app must be served over HTTPS (or localhost during development).
