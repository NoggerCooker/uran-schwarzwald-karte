# Uranvorkommen im Schwarzwald – Übersichtskarte

Kleine Leaflet-Karte mit historischen Fund- und Prospektionsgebieten.

## Behobener Tile-Fehler

Die Karte verwendet jetzt den offiziellen OpenStreetMap-Endpunkt:

```text
https://tile.openstreetmap.org/{z}/{x}/{y}.png
```

Die Datei ist für das direkte Öffnen per `file://` vorbereitet. Es ist kein lokaler HTTP-Server erforderlich. Einfach `index.html` im Browser öffnen.

Wichtig: Der öffentliche OSM-Tile-Dienst ist kostenlos, aber nur für angemessene Nutzung gedacht. Die korrekte OpenStreetMap-Attribution ist in der Karte enthalten.

## Start

`index.html` direkt im Browser öffnen (Doppelklick oder **Datei → Öffnen**). Ein lokaler HTTP-Server ist nicht erforderlich.

Die Karte lädt die aktuell sichtbaren Kacheln interaktiv von OpenStreetMap. Eine Internetverbindung ist dafür notwendig.

## Hinweis

Die Marker sind Orts- bzw. Gebietsmitten und keine verifizierten Stolleneingänge oder exakten Erzpunkte. Für die Kartenanzeige ist eine Internetverbindung zum Leaflet-CDN und zum OpenStreetMap-Kachelserver erforderlich.
