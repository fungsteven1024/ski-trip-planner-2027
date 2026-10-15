# Ski Trip Planner & Cost Splitter

A single-page, offline-friendly planner for a two-family ski trip (depart Wed Feb 17, 2027, return Sun Feb 21, 2027, 4 nights) with **Colorado** and **Utah** tabs:
flights, lodging (slopeside / Airbnb / hotel), lift tickets and rentals, an optional hot spring day,
rental-car comparison, an interactive map, and a per-family cost split. English / 中文 toggle.

- Open `index.html` in a browser; no build step and no API keys needed.
- Inputs are saved in your browser's localStorage only; use **Reset** to restore defaults.
- Prices are estimates or labeled TBD, with sources linked; verify before booking.
- Map: [Leaflet](https://leafletjs.com/) (vendored in `vendor/`, BSD-2-Clause) with © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors tiles. Utah drive times, and Colorado segments other than the airport, are precomputed with the [OSRM](https://project-osrm.org/) public router (no traffic). Colorado times from DEN are approximate published driving estimates.
