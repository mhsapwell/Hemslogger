# HEMS Logger (hardened build)

Single-file app. Designed to avoid iOS homescreen white-screen by:
- Global error overlay (surfaces any JS error).
- Safe localStorage fallback (no-ops if blocked).
- UUID polyfill.
- OS Grid GPS conversion.

## Deploy
Upload index.html to GitHub Pages (main/root). Open in Safari, then Add to Home Screen.

## If you previously saw a white screen
Delete the old Home Screen icon first. If you ever deployed a service worker for this domain, clear Safari → Settings → Advanced → Website Data → Remove for your site.
