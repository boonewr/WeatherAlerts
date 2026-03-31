# SkyAlert

A single-page weather alert dashboard that shows current and recent NWS alerts for your location, alongside live weather conditions.

## Features

- **Live NWS alerts** — active and past 7-day alerts, split by county and statewide
- **Current weather** — temperature, feels like, humidity, UV index, pressure, and wind via [Open-Meteo](https://open-meteo.com)
- **48-hour forecast** — daily high/low for the next two days
- **Interactive map** — Leaflet map with alert polygons color-coded by type and severity
- **Location search** — search any US city, county, or zip code; or snap back to your current location

## Usage

No build step. Open `index.html` directly in a browser. Also available via GitHub Pages at: [SkyAlert | Weather Intelligence](https://boonewr.github.io/WeatherAlerts/index.html).

Location access must be granted on first load. All data is fetched client-side from public APIs — no backend or API keys required.

## Data Sources

| Data | Source |
|---|---|
| Weather alerts | [NWS API](https://www.weather.gov/documentation/services-web-api) |
| Current weather & forecast | [Open-Meteo](https://open-meteo.com) |
| Geocoding & search | [Nominatim / OpenStreetMap](https://nominatim.org) |
| Map tiles | [CARTO](https://carto.com) |
