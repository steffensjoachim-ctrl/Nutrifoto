# NutriFoto PWA MVP

## Lokal starten
Im Ordner einen lokalen Webserver starten, z. B.:

    python3 -m http.server 8080

Dann `http://localhost:8080` öffnen. Für Kamerazugriff und Installation auf einem Smartphone ist HTTPS erforderlich.

## Enthalten
- Fünf Screens: Heute, Foto, Analyse/Korrektur, Speichern, Historie
- lokale Speicherung via localStorage
- CSV-Export
- Offline-Grundfunktion via Service Worker
- installierbares PWA-Manifest

## Wichtig
Die Fotoanalyse ist im kostenlosen MVP bewusst simuliert. Es wird kein Bild hochgeladen. Für echte KI-Erkennung muss später ein sicherer Backend-Endpunkt ergänzt werden; API-Schlüssel niemals im Browser speichern.
