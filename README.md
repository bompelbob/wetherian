# WETTER

Eine persönliche Wetter-Web-App im reduzierten LCARS-Look.

Die App zeigt eine 72-Stunden-Prognose mit mehreren Wettermodellen, eine kompakte Tagesübersicht, Regenradar, Favoritenorte und eine einfache Standortwahl. Sie ist für die Nutzung auf dem iPhone als PWA gedacht und funktioniert komplett clientseitig.

## FEATURES

- 72-STUNDEN-DIAGRAMM
- TAGESÜBERSICHT
- RADAR
- ORTE & FAVORITEN
- PWA (Homescreen, Offline-Cache)

## DATENQUELLEN & LIZENZEN

Diese App verwendet externe Daten- und Kartendienste. Es gelten die jeweiligen Lizenzbedingungen der Anbieter:

### Wetterdaten
- OPEN-METEO  
  https://open-meteo.com/  
  Nutzung gemäß deren API- und Lizenzbedingungen.

### Radar
- RAINVIEWER  
  https://www.rainviewer.com/api.html  
  Nutzung gemäß deren API- und Lizenzbedingungen.

### Karten
- LEAFLET (JavaScript Library)  
  https://leafletjs.com/  
  Lizenz: BSD-2-Clause

- CARTO Basemaps  
  https://carto.com/attributions  
  © OpenStreetMap contributors © CARTO  
  Nutzung gemäß den jeweiligen Nutzungsbedingungen.

## TECHNIK

- HTML / CSS / JavaScript
- Leaflet
- Service Worker
- LocalStorage

## INSTALLATION

```bash
python3 -m http.server 8000
```

Dann öffnen:

http://localhost:8000

## HINWEIS

Diese App wird ohne Gewähr bereitgestellt. Für die Richtigkeit, Verfügbarkeit und Aktualität der Wetter- und Radardaten wird keine Haftung übernommen.

## AUTOR

Alexander
