CNC-Rechner – PWA für PWABuilder

Dateien:
- index.html: Anwendung (Version 6: Fräsen, Drehen, Bohren, Gewinde, Passung, Info; Deutsch/Englisch)
- manifest.json: PWA-Manifest
- sw.js: Service Worker für Offline-Cache (Cache-Name cnc-rechner-v6)
- icon-32.png / icon-180.png: App-Icons

Für GitHub Pages: Lade diese Dateien in denselben Ordner/Repository wie deine Website hoch
(vorhandene Dateien mit gleichem Namen ersetzen).
Die Startseite muss über HTTPS erreichbar sein. Danach die URL der veröffentlichten index.html bzw. Website bei PWABuilder prüfen.

Hinweis zum Update: Der Service Worker nutzt einen Cache. Wird eine neue Version hochgeladen,
muss der Cache-Name in sw.js (CACHE = 'cnc-rechner-vX') erhöht werden, sonst zeigt das Gerät weiter die alte Version.
