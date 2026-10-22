beadshop PWA
=============

This folder contains your 3D bracelet viewer converted into a Progressive Web App.

Files:
- index.html       Your viewer with PWA support added
- manifest.json    App name/icon/display settings
- sw.js            Service worker for app-style loading/caching
- icon-192.png     App icon
- icon-512.png     App icon

IMPORTANT:
Chrome normally requires the app to be served from HTTPS (or localhost) before
"Install app" / "Add to Home screen" works as a real PWA.

After hosting these files at an HTTPS address:
1. Open the address in Chrome on Android.
2. Open the Chrome menu (⋮).
3. Choose "Install app" if offered, or "Add to Home screen".
4. Launch it from the new beadshop icon.

The viewer itself still loads Three.js from its existing CDN URL, so an internet
connection is recommended, especially the first time.
