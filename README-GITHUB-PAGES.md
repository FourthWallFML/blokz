# Blokz — Standalone GitHub Pages Pakket

Deze ZIP bevat alles wat je nodig hebt om **Blokz** direct en gratis op **GitHub Pages** te zetten (inclusief PWA-installatie op tablet, telefoon en desktop).

## Bestanden in dit pakket
- `index.html` — De volledige Blokz applicatie
- `manifest.json` — PWA Web App Manifest (naam, iconen en standalone modus)
- `sw.js` & `ws.js` — Service Worker voor offline ondersteuning
- `assets/` — Gebundelde JavaScript en CSS bestanden
- `pwa-192x192.png`, `pwa-512x512.png`, `pwa-maskable-512x512.png`, `apple-touch-icon.png`, `icon.svg` — App-icoontjes
- `.nojekyll` — Zorgt dat GitHub Pages alle bestanden zonder aanpassing serveert

## In 4 stappen op GitHub Pages zetten
1. Maak een nieuwe (publieke) repository aan op [github.com](https://github.com), bijvoorbeeld `blokz`.
2. Pak deze ZIP uit en upload alle bestanden uit de map direct in de hoofdmap (`main` branch) van je repository.
3. Ga in je repository naar **Settings → Pages**.
4. Kies bij **Build and deployment → Branch** voor `main` en map `/ (root)`, en klik op **Save**.

Na ongeveer 1 minuut staat jouw persoonlijke Blokz-app live op:
`https://<jouw-gebruikersnaam>.github.io/<repository-naam>/`

Op een iPad of Android-tablet kun je de pagina daarna via **Deel → Zet op beginscherm** (of de knop **Installeer app**) als echte app op het startscherm plaatsen.
