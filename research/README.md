# Crete Experience Research v3 — Location Search

Open `research/index.html` or publish the `research/` folder on GitHub Pages. The geocoding search (Map & locations) sends explicit, user-submitted place names to OpenStreetMap Nominatim. It does not autocomplete. Search choices are temporary; selecting **Use as my base** saves only latitude/longitude to this browser's localStorage to calculate straight-line distances from the base to public locality estimates. It is **not** the private home address unless you select that location. Neither searches nor local private-base coordinates are embedded in code, exported with the research data, or committed to Git. External map servers receive map-tile requests for locations viewed, as with other online maps.

Operators and experience records: 111 (unchanged from v2). Map uses OpenFreeMap and MapLibre for live tiles. Offline data view remains available when the map service is unavailable.
