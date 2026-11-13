SAVE OR DONATE — INSTALLABLE AND OFFLINE PWA

This is a Progressive Web App package. It is not a compiled APK.
It must first be hosted on an HTTPS address to enable installation and offline caching.

PHONE-ONLY SETUP (one possible route):
1. Extract this ZIP on your Android phone.
2. Open a hosting provider that supports static site upload (for example Cloudflare Pages Direct Upload or Netlify Drop) and create a free static site.
3. Upload the CONTENTS of this folder (index.html, manifest.webmanifest, sw.js, icons folder) to the site root.
4. Open the resulting HTTPS site in Chrome.
5. Use Chrome menu > Add to Home screen / Install app.
6. Launch from the new home-screen icon. After the first successful load, the app shell is cached for offline use.

IMPORTANT DATA NOTE:
Challenge entries are stored locally in the browser/app origin using localStorage. Keep using the same installed app/site and periodically export a JSON backup from Challenge History. Clearing site/app data or uninstalling can erase local data. The JSON backup is the recovery copy.
