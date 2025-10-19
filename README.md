# HEMS Logger (final build)

Single-file build of the HEMS Fuel/Flight Logger.

## Deploy (GitHub Pages)
1) Create or open repo (e.g. `Hemslogger`), branch `main`.
2) Replace **index.html** with this file.
3) In repo Settings → Pages → Source: **Deploy from a branch** → Branch: **main / root**.
4) Open https://<your-user>.github.io/<repo>/ in Safari.

## Notes
- Storage is `localStorage` (key: `hems_min_logger_v6_preview`). Private Browsing may not persist.
- No service worker is included to avoid iOS “white screen” PWA issues. You can add one later.
- The **Date** field always mirrors the **Landing** date. “Update Now” refreshes both.
- Fuel added (L) auto-converts to kg using density 0.8 and adds to start fuel.
