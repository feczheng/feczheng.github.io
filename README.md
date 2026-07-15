# Hong Kong Licensed Restaurant Cuisines (January 2016–January 2025)

Interactive point map for ten January snapshots of Hong Kong licensed restaurants. Data were collected and the website was created by Zheng Gang, Department of Geography, The University of Hong Kong, under the supervision of Prof. Peter K. Koh.

## Data scope

- Food and Environmental Hygiene Department (FEHD) licensed-restaurant stock in each January snapshot.
- OpenRice Hong Kong labels collected in 2025, plus manually verified online sources, supplement cuisine identification.
- Counts are licence-stock snapshots, not annual openings, closures, sales, or real-time operating status.
- Source labels `Mainland China` and `Chinese Mainland` are aliases and are both displayed as `Chinese Mainland`.
- `Hong Kong Style` is displayed as `Hong Kong-style`; `Taiwan` is displayed as `Taiwanese`.
- The residual `Other` category contains only records labelled `Other` or an otherwise unrecognised source label.

The canonical display categories are `Hong Kong-style`, `Western`, `Chinese Mainland`, `Japanese`, `Korean`, `Taiwanese`, `Vietnamese`, `Thai`, and `Other`.

## Data files

The page reads these source CSVs without modifying them:

- `data/201601_processed.csv`
- `data/201701_processed.csv`
- `data/201801_processed.csv`
- `data/201901_processed.csv`
- `data/202001_processed.csv`
- `data/202101_processed.csv`
- `data/202201_processed.csv`
- `data/202301_processed.csv`
- `data/202401_processed.csv`
- `data/202501_processed.csv`

Required columns are `Main_Cuisine`, `Longitude`, and `Latitude`; `Name` is optional. The ten all-category totals are `13,478`, `13,869`, `14,461`, `14,986`, `15,455`, `15,880`, `16,412`, `16,812`, `16,966`, and `16,729`.

## Interpretation

Marker clusters and the heat layer are exploratory display tools. The heat layer uses screen-space pixels and changes with zoom; it is not the manuscript's projected 400 m kernel-density estimate, net-change surface, or footprint measure. Use the explicit **Fit** button when a new extent is wanted so that year-to-year map comparisons keep a stable viewport.

## Run locally

Serve the repository with any static web server, for example:

```bash
python3 -m http.server 8080
```

Then open `http://127.0.0.1:8080/`.

## Acknowledgements

Map tiles and data © OpenStreetMap contributors. Built with Leaflet, Leaflet.markercluster, Leaflet.heat, Papa Parse, and D3.

© 2026 Zheng Gang. All rights reserved. Library copyrights belong to their respective owners.
