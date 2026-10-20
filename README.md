# Auftragsnummern als QR-Code

Eine mobil optimierte, statische Web-App für den schnellen Einsatz auf dem Smartphone. Auftragsnummern werden in einer Liste auf dem Gerät gespeichert. Ein Tipp auf einen Eintrag öffnet den QR-Code bildschirmfüllend.

## Auf GitHub Pages verwenden

Die vorhandene GitHub-Actions-Konfiguration veröffentlicht Änderungen aus `main`. Die URL findest du unter **Settings → Pages**. Auf dem Handy kannst du die Seite im Browser öffnen und bei Bedarf zum Home-Bildschirm hinzufügen.

## Bedienung

1. Auftragsnummer ins Eingabefeld schreiben und **Hinzufügen** tippen.
2. Den Auftrag in der Liste antippen, um den QR-Code groß anzuzeigen.
3. Über **Zurück** oder die Zurück-Geste wieder zur Liste wechseln.
4. Nicht mehr benötigte Einträge über **×** löschen.

Die Auftragsliste bleibt im lokalen Speicher dieses Browsers auf diesem Gerät. Sie wird nicht zwischen Geräten synchronisiert. Für das QR-Bild wird die Auftragsnummer an `api.qrserver.com` übertragen.