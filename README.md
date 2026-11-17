# Elki

## NOVA Budget

Die Startseite `index.html` enthält eine responsive, deutschsprachige Budget-App im Dark-Glass-Design.

- Einnahmen und Ausgaben mit Datum erfassen, bearbeiten und löschen
- Kategorien alphabetisch sortiert und eigene Kategorien
- Monatsbudgets pro Kategorie
- Kreisdiagramm mit Prozentanteil und CHF-Betrag
- Monatssummen und automatische Trennung nach Kalendermonat
- CSV-Export und JSON-Backup / Import
- Währungsanzeige einstellbar (Standard CHF)
- PWA-Grunddateien: `manifest.json` und `sw.js`

### Veröffentlichung
GitHub Pages für dieses Repository aktivieren (Settings → Pages → Deploy from a branch → main / root). Danach kann die Seite über die GitHub-Pages-Adresse geöffnet und auf dem iPhone in Safari über Teilen → Zum Home-Bildschirm installiert werden.

### Datenspeicherung und Grenzen
Die App speichert Buchungen im LocalStorage des jeweiligen Browsers. Es gibt keine Cloud-Synchronisierung, Bankanbindung, echte Passwortverschlüsselung oder externe KI. Währungswechsel ändert nur die Anzeige und rechnet bestehende Beträge nicht um. Für geräteübergreifende Synchronisierung und sicheren Mehrbenutzerbetrieb ist ein Backend nötig.
