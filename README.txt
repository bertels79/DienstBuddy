Schichtiva V3.4 – Testversion

Basis: getestete Schichtiva V3.3.

Neu:
- Biometrischer App-Schutz über WebAuthn.
- Entsperrung je nach Gerät mit Fingerabdruck, Gesichtserkennung oder Geräte-PIN.
- Einrichtung/Deaktivierung unter Einstellungen -> App-Schutz.
- Automatische Sperre beim Start, wenn Schutz aktiviert ist.
- Nach mehr als 15 Sekunden im Hintergrund wird beim Zurückkehren erneut gesperrt.
- Biometrische Daten werden NICHT in Schichtiva gespeichert.
- Nur eine technische WebAuthn-Kennung wird lokal gespeichert.
- Bestehende V3.3-Funktionen bleiben erhalten.

WICHTIG FÜR DEN TEST:
WebAuthn benötigt eine sichere HTTPS-Adresse.
Nicht per lokaler file://-Datei testen.
Für den Handy-Test die raw.githack-HTTPS-Testadresse verwenden.

Hinweis:
Die WebAuthn-Anmeldung ist an die jeweilige Web-Domain gebunden.
Wenn Schichtiva später auf eine andere endgültige Domain umzieht, muss der
App-Schutz dort einmal neu eingerichtet werden.

Noch nicht nach main übernehmen.
