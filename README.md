# HEMS Logger (homescreen-safe)

This build includes layout fixes for iOS Home Screen (standalone) mode:
- Dynamic bottom padding that matches the footer’s height (prevents overlap).
- Uses safe-area insets and adjusts on keyboard open/close via `visualViewport`.
- Hardened against iOS white screen with an error overlay and safe storage.
- OS Grid GPS.

## Deploy
Upload `index.html` to GitHub Pages (root, main). Open in Safari, then Share → Add to Home Screen.
