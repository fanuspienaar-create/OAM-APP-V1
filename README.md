# OAM Studio v6 — Responsive + PWA Fix

This build keeps the OAM Studio v5 functionality and fixes the responsive/PWA foundation:
- iPhone portrait + landscape
- Android portrait + landscape
- PC/desktop and landscape tablet layouts
- OAM logo uses PNG with an embedded fallback
- OAM app icons include iOS 180px, Android 192px and 512px assets
- manifest declares orientation: any
- iOS PWA meta tags and Apple touch icons
- service worker cache bumped to v6 to invalidate old cached assets

## GitHub Pages
Upload the contents of this folder to the repository root. Keep the `assets` folder beside `index.html`, `manifest.webmanifest`, and `sw.js`.

If an older installed PWA still shows the old UI, remove the old home-screen shortcut and add the GitHub Pages site again after the new deployment is live.
