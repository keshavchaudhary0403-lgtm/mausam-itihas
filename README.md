# Mausam Itihas

Historical weather for any place in India: 5, 10 or 15 years of daily temperature and rainfall, a daily-actuals explorer, and a 7-day forecast compared with normal.

A single static page (`index.html`) with no build step. Data comes from the browser at runtime:

- **History and forecast:** [Open-Meteo](https://open-meteo.com/) (ERA5 reanalysis, multi-model forecast)
- **Place search:** Open-Meteo geocoding, Photon and Nominatim (OpenStreetMap)
- **Map picker:** Leaflet with OpenStreetMap and Esri imagery

## Deploy

Hosted on Vercel, connected to this repo. Every push to `main` deploys automatically.
