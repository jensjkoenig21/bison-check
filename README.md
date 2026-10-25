# BISON Radar V1.24 – GitHub Pages / PWA

## GitHub Pages
1. In deinem BISON-Radar-Repository diese drei Dateien ins Hauptverzeichnis laden:
   - index.html
   - manifest.webmanifest
   - sw.js
2. In GitHub: Settings → Pages.
3. Unter "Build and deployment" → "Deploy from a branch".
4. Branch `main`, Ordner `/(root)` auswählen und speichern.
5. Die von GitHub angezeigte Pages-Adresse in Safari auf dem iPhone öffnen.

## iPhone
Wenn die Seite in Safari sauber läuft:
Teilen → Zum Home-Bildschirm → Hinzufügen.

Danach startet BISON Radar im Standalone-Modus wie eine App.

## Wichtig
Portfolio, Trades, Intelligence und Forecast-Historie verwenden weiterhin localStorage.
PC und iPhone haben deshalb vorerst getrennte lokale Datenbestände.
Das ist bewusst so: Erst Mobile/PWA stabilisieren, danach Synchronisation ergänzen.
