Litixy Calendar — PWA package

Included
- index.html: app entry point (recommended URL)
- Litixy_Calendar.html: same app with the original filename
- manifest.webmanifest: install metadata and app icons
- sw.js: offline app-shell cache and update handling
- icons/: browser, home-screen, and maskable app icons

Publish and install
1. Upload ALL files and folders in this package to the same directory on an HTTPS website.
   GitHub Pages, Netlify, and other static HTTPS hosts are suitable.
2. Open the published index.html address in a supported browser.
3. Select "アプリとして使う" in Litixy Calendar when the browser provides an install prompt.
   - iPhone / iPad: open the site in Safari → Share → "ホーム画面に追加".
   - Android: open in Chrome → menu → "アプリをインストール" or "ホーム画面に追加".
   - Desktop: use the install icon in the address bar or the browser menu.

Important
- PWA installation and Service Workers require HTTPS, except localhost during development.
- Opening the HTML file directly using file:// does NOT enable PWA installation or offline caching.
- Existing calendar entries are still stored in this browser's localStorage. PWA installation does not synchronize events across devices or browsers.
- Keep index.html, manifest.webmanifest, sw.js, and icons/ together at the same site path.
