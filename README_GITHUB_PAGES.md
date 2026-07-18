# SET/5 v0.8 – GitHub Pages

## Veröffentlichen

1. Den **Inhalt dieses Ordners** in die Root-Ebene eines GitHub-Repositories hochladen.
2. In GitHub `Settings → Pages` öffnen.
3. Unter **Build and deployment** `Deploy from a branch` auswählen.
4. Branch `main` und Ordner `/(root)` wählen.
5. Nach dem Deployment die angezeigte HTTPS-Adresse öffnen.

Wichtig: Nicht den übergeordneten Ordner als Unterordner hochladen. `index.html`, `sw.js` und `manifest.webmanifest` müssen nebeneinander in der veröffentlichten Root-Ebene liegen.

## iPhone

1. Die GitHub-Pages-Adresse in Safari öffnen.
2. `Teilen → Zum Home-Bildschirm` wählen.
3. Nach dem ersten vollständigen Laden funktioniert die App auch offline.

## Updates

Neue Dateien in dasselbe Repository hochladen und committen. Sobald der Service Worker die neue Version geladen hat, zeigt SET/5 einen Update-Hinweis auf dem Startbildschirm.

## Speichern

Run, Einstellungen, Data, Startsets und Sammlung liegen im lokalen Browserspeicher der jeweiligen GitHub-Pages-Adresse. Eine Änderung der Repository- oder Domain-Adresse erzeugt einen neuen Speicherbereich.
