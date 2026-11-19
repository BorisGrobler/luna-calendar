LUNA CALENDAR — iPhone PWA package

Files:
- index.html: app
- manifest.webmanifest: install metadata
- service-worker.js: offline cache
- icons/: app icons

IMPORTANT:
A PWA must be served from HTTPS (or localhost) to install and use service workers.
You cannot install it by opening the HTML file from the iPhone Files app.

To install on iPhone:
1. Upload this folder's contents to an HTTPS static host.
2. Open the HTTPS URL in Safari.
3. Tap Share -> Add to Home Screen.
4. Enable "Open as Web App" if iOS offers it, then tap Add.
5. Open Luna from the Home Screen once while online; then it should be cached for offline use.

This package is self-contained and does not use third-party libraries.
