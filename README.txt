WIFI CSI AI DASHBOARD – PWA PROTOTYP

Inhalt:
- index.html: Dashboard-Oberfläche mit simulierten Demo-Daten
- manifest.webmanifest: PWA-Metadaten
- sw.js: Offline-Cache (Service Worker)
- icon.svg: App-Symbol

WICHTIG:
Alle angezeigten Werte sind synthetische Demo-Daten. Es gibt keine echte CSI-Erfassung, keine reale Körper-Keypoint-Erkennung und keine medizinische Vitalmessung.

PWA-INSTALLATION:
Eine PWA benötigt für Installation und Service Worker normalerweise HTTPS (oder localhost).
1. Dateien auf einen HTTPS-Webhost hochladen.
2. Auf dem Samsung Galaxy Tab S7+ in Chrome die HTTPS-Adresse öffnen.
3. Browser-Menü öffnen und „App installieren“ oder „Zum Startbildschirm hinzufügen“ wählen.

LIVE-MODUS:
Die Oberfläche enthält bereits ein Feld zum Vormerken einer späteren Gateway-Adresse. Es findet noch keine Verbindung statt. Für Live-Daten müssen ESP32-Firmware, CSI-Gateway, API/Datenformat und passende Auswertealgorithmen implementiert und getestet werden.
