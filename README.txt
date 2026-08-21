Schichtiva V4 – ScanFix

Neu im Scanner:
- Parser 3.0 mit räumlicher Kalender-Screenshot-Erkennung.
- Tesseract-Koordinaten werden gespeichert und ausgewertet.
- Kalendertage werden als Raster erkannt.
- Schichttexte unter einem Datum werden dem passenden Kalendertag zugeordnet.
- Statusleisten-Uhrzeiten wie 23:11 werden nicht als Schicht interpretiert.
- Monatsname aus dem Screenshot wird zur Datumsbildung verwendet.
- Gespeicherte Schichtnamen wie „Früh kurz“ werden direkt erkannt.
- Codes wie F2/S2 bleiben unterstützt.
- Klassische Text-/Tabellen-Dienstpläne nutzen weiterhin den bisherigen Parser als Fallback.

Testfall:
Kalender-Screenshot mit Einträgen wie „Früh (F2) 06:30“, „Früh kurz 06:20“ und „Spät (S2) 14:00“.

Vor Veröffentlichung bitte mit den bereitgestellten Kalender-Screenshots testen.
