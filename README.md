# WETTER

Eine persönliche Wetter-Web-App im reduzierten LCARS-Look.

Die App zeigt eine 72-Stunden-Prognose mit mehreren Wettermodellen, eine kompakte Tagesübersicht für die nächsten Tage, Regenradar, Favoritenorte und eine einfache Standortwahl. Sie ist für die Nutzung auf dem iPhone als PWA gedacht und funktioniert komplett clientseitig.

## FEATURES

- 72-STUNDEN-DIAGRAMM
  - Temperaturkurven von ECMWF, ICON und GFS
  - Niederschlagsbalken im Diagramm
  - interaktiver Tooltip per Touch
  - Tageswechsel und Zeitraster

- TAGESÜBERSICHT
  - kompakte Vorschau für die nächsten Tage
  - Wettericons
  - Min- und Max-Temperaturen
  - Niederschlagsmenge pro Tag

- RADAR
  - aktuelles Regenradar auf Karte
  - zentriert auf den gewählten Ort

- ORTE
  - Ortssuche
  - aktueller Standort per Geolocation
  - Favoriten mit aktueller Temperatur

- PWA
  - Homescreen-fähig
  - Fullscreen-Nutzung auf iPhone
  - einfacher Offline-Fallback über Cache

## VERWENDETE DATENQUELLEN

- Wetterdaten: OPEN-METEO
- Radar: RAINVIEWER
- Karte: LEAFLET mit Basemap von CARTO

## TECHNIK

- HTML
- CSS
- Vanilla JavaScript
- Leaflet
- Open-Meteo API
- RainViewer Radar Tiles
- LocalStorage
- Service Worker

## PROJEKTZIEL

Das Projekt ist als persönliche, schnelle und lesbare Wetter-App gedacht.

Der Fokus liegt auf:

- klarer Darstellung
- schneller Benutzung
- keinem Login
- keinem Tracking
- keiner Werbung
- keinem Abo

## INSTALLATION

### Lokal testen

```bash
python3 -m http.server 8000
```

Dann im Browser öffnen:

http://localhost:8000

## NUTZUNG ALS PWA AUF DEM IPHONE

1. Seite in Safari öffnen
2. Teilen-Menü öffnen
3. „Zum Home-Bildschirm“ wählen
4. App starten

## CACHING

Die App speichert lokal:

- aktuellen Ort
- Favoriten
- zuletzt geladene Wetterdaten
- Radarzeitstempel

## AUTOR

Alexander
