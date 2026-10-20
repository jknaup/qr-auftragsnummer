# QR-Code für Auftragsnummern

Eine kleine statische Web-App: Auftragsnummer eingeben, QR-Code anzeigen, herunterladen oder drucken. Kein Build-Schritt und kein Backend erforderlich.

## GitHub Pages aktivieren

1. In GitHub **Settings → Pages → Build and deployment → Source** die Option **GitHub Actions** wählen.
2. Auf `main` pushen. Der Workflow veröffentlicht die Seite automatisch.
3. Die URL findest du unter **Settings → Pages**.

## Verwendung

`index.html` öffnen oder die Pages-URL aufrufen, Auftragsnummer eingeben und **QR-Code erstellen** wählen. Mehrere Nummern können zeilenweise eingegeben werden; pro Klick wird die Eingabe als ein QR-Code codiert.

Die QR-Grafik wird über `api.qrserver.com` geladen. Die Auftragsnummer wird dazu an diesen externen Dienst gesendet. Für rein lokale Generierung kann die QR-Bibliothek später direkt im Projekt mitgeführt werden.
