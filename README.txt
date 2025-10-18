# HEMS Logger (PWA)

Installable flight & fuel logger. Works offline. Data stored locally per device (Local Storage).
- Added fuel in litres; auto-converted to kg at 0.8 and added to start fuel silently.
- GPS button fills 6-figure OS Grid (GB only) from device location.
- Records appended to the bottom; start fuel for next entry is last landing fuel.
- Export CSV of visible records (Today/All).

## Hosting (GitHub Pages)
1) Create a new repo (e.g., hems-logger) and upload all files.
2) In repo settings -> Pages -> Deploy from branch -> select main and root.
3) Wait for the site to publish at https://<username>.github.io/hems-logger
4) Open on iPhone Safari -> Share -> Add to Home Screen.

## Local testing
Serve these files over HTTP (not just open as file://) for service worker:
- Python:  python3 -m http.server 8000
- Open:    http://localhost:8000

## Files
- index.html
- manifest.webmanifest
- sw.js
- icons/icon-192.png, icons/icon-512.png