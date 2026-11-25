# Blokz — Standalone GitHub Pages Pakket (Geen submappen!)

Alle JavaScript, CSS en het Blokz-logo zitten volledig ingebouwd in **één enkel `index.html`-bestand**.
Er is **geen `assets`-map** meer nodig!

## Bestanden in dit pakket (allemaal los in de hoofdmap)
- `index.html` — De volledige, zelfstandige Blokz applicatie (werkt zelfs helemaal los!)
- `manifest.json` — PWA Web App Manifest (naam, iconen en app-modus)
- `sw.js` & `ws.js` — Service Worker voor offline ondersteuning
- `pwa-192x192.png`, `pwa-512x512.png`, `pwa-maskable-512x512.png`, `apple-touch-icon.png`, `icon.svg` — App-icoontjes
- `.nojekyll` — Zorgt dat GitHub Pages alle bestanden zonder aanpassing serveert

## In 4 stappen op GitHub Pages zetten
1. Maak een nieuwe (publieke) repository aan op [github.com](https://github.com), bijvoorbeeld `blokz`.
2. Klik op **Add file → Upload files** en sleep de losse bestanden uit deze ZIP (of alleen `index.html`) naar GitHub.
3. Ga in je repository naar **Settings → Pages**.
4. Kies bij **Build and deployment → Branch** voor `main` en map `/ (root)`, en klik op **Save**.

Na ongeveer 1 minuut staat jouw persoonlijke Blokz-app live op:
`https://<jouw-gebruikersnaam>.github.io/<repository-naam>/`
