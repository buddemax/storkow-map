# Storkow (Mark) – Wichtige Orte in Ihrer Nähe

Interaktive Karte & Poster der wichtigsten Orte rund um **Friedensdorf 4, 15859 Storkow (Mark)**.

- Alle Standorte gegen echte OpenStreetMap-Daten verifiziert
- Entfernungen (Fußweg & Auto) als reale Routen via OSRM berechnet – keine Luftlinie
- Flache, gut lesbare Vektorkarte (Grün, Wasser, Straßen) statt Kachel-Detail

## Seiten

| Datei | Inhalt |
|-------|--------|
| [`index.html`](index.html) | Interaktive Karte (Leaflet): nummerierte Marker, klickbare Liste, Zoom |
| [`export.html`](export.html) | Poster – nur nummerierte Marker + Legende/Liste |
| [`export2.html`](export2.html) | Poster – mit Namen & Adressen (Rand-Spalten, überlappungsfrei) |
| `storkow_karte.png` / `.pdf` | Export der Nummern-Version |
| `storkow_karte_labels.png` / `.pdf` | Export der Beschriftungs-Version |
| [`map_data.json`](map_data.json) | Datenquelle (Orte, Koordinaten, Distanzen) |

## Technik

Statische Site, kein Build. Karte: [Leaflet](https://leafletjs.com/).
Kartendaten © OpenStreetMap-Mitwirkende · Routing: OSRM (routing.openstreetmap.de).

## Lokal starten

```sh
python3 -m http.server 8090
# http://localhost:8090/
```
