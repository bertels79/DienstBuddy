DienstBuddy V3.0 – PWA-Installationsfix

Neu:
- vollständiges PWA-Manifest mit 192x192- und 512x512-App-Icons
- eindeutige App-ID, Scope und Standalone-Modus
- Android-/iPhone-PWA-Metadaten
- Service Worker auf V3.0 aktualisiert
- Start-URL auf ?v=30 aktualisiert
- alle Funktionen aus V2.9 bleiben erhalten

GitHub:
Alle Dateien aus diesem ZIP ins Repository hochladen/ersetzen:
index.html
manifest.webmanifest
service-worker.js
icon-192.png
icon-512.png

Wichtig beim Test:
Die alte DienstBuddy-Verknüpfung vom Startbildschirm zuerst löschen.
Danach https://bertels79.github.io/DienstBuddy/?v=30 in Chrome öffnen.
Dann Chrome-Menü > Installieren und Verknüpfen.
Wenn Chrome die PWA erkennt, sollte DienstBuddy als eigenständige App installiert werden.
