Bill Split App V58 - PWA Version

What changed:
- Added PWA manifest.
- Added iPhone Home Screen support.
- Added service worker for offline app shell caching after first load.
- Added app icons.
- Added index.html as the main launch file.

Important:
Do not open this from iPhone Files Preview. iOS Preview can show the page but buttons will not work.

Recommended use:
1. Upload this folder to GitHub Pages, Netlify, or Vercel.
2. Open the hosted URL in Safari on iPhone.
3. Tap Share > Add to Home Screen.
4. Launch from the Home Screen icon.

Local Mac testing:
1. Open Terminal in this folder.
2. Run: python3 -m http.server 8000
3. Open http://localhost:8000 on Mac, or http://YOUR-MAC-IP:8000 on iPhone while on the same Wi-Fi.

Notes:
- Offline mode works after the first successful hosted load.
- OCR/PDF libraries may still need internet the first time if loaded from CDN.

V62: Fix startup crash caused by removed dark mode button so first-load data renders immediately.
