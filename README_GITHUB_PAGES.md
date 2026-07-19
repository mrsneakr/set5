# SET/5 – GitHub Pages v1.9

## Wichtig

v1.9 behebt einen JavaScript-Fehler, durch den der Shop nur teilweise gerendert wurde.

Außerdem enthält die Version eine vollständige Vereinheitlichung von:

- Abständen
- Schriftgrößen
- Konturen
- Schatten
- Board
- Shop
- Dialogen
- Overlays
- responsive Höhen

## Deployment

Den vollständigen Inhalt dieses Ordners in die Root-Ebene des Repositories kopieren:

- `index.html`
- `404.html`
- `manifest.webmanifest`
- `sw.js`
- `.nojekyll`
- `icons/`

Der Service Worker verwendet den Cache `set5-v1.9.0`.

Nach dem Deployment:

1. Seite vollständig neu laden.
2. Home-Screen-App vollständig schließen.
3. App erneut öffnen.
4. Bei weiterhin alter Version Website-Daten beziehungsweise den alten PWA-Cache entfernen.
