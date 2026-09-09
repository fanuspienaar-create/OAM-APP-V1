# OAM Studio — One Stop Artist Marketing Studio

## IMPORTANT — GitHub Pages upload
Upload the **contents of this folder into the ROOT of your repository**. Your repository must show `index.html`, `manifest.webmanifest`, `sw.js`, `.nojekyll`, and the `assets` folder at the same level. Do not put them inside a second `OAM_Studio` folder.

This build fixes the previous fatal JavaScript syntax error that stopped the app buttons/navigation from working. The OAM logo has an embedded WebP fallback, so a bad GitHub asset path cannot leave a broken `?` image. The service worker is versioned and uses network-first updates so old cached builds are removed.

## GitHub Pages
Settings → Pages → Deploy from branch → `main` → `/ (root)` → Save.

After replacing an older deployment, open the site once in a private/incognito tab or clear the installed site's data if an old service worker is still showing.
