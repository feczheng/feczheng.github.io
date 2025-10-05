# Hong Kong Restaurant Cuisines (2018–2023)

Data collected and website created by **Zheng Gang**.  
Supervised by **Prof. Peter K. Koh** (HKU).

## Author
**Zheng Gang**  
PhD Candidate, Department of Geography, The University of Hong Kong (HKU)

## Data format
- CSV columns required: `Main_Cuisine`, `Longitude`, `Latitude`
- Optional: `Name`
- Default file paths under `data/`:
  - `201801_processed.csv`
  - `201901_processed.csv`
  - `202001_processed.csv`
  - `202101_processed.csv`
  - `202201_processed.csv`
  - `202301_processed.csv`

## Quick start (local)
Open `index.html` with any static server (e.g., VS Code Live Server).

## Deploy to GitHub Pages
- Personal site: create repo `your-username.github.io`, put files in root, visit `https://your-username.github.io/`
- Project site: any repo → Settings → Pages → Deploy from a branch → `main` → `/root`

## Notes
- Keep OSM/CARTO attributions.
- If performance is an issue with many points, switch to Heatmap mode or pre-aggregate points (e.g., 400m hex bins).

## Acknowledgements
- Map tiles & data © OpenStreetMap contributors.  
- Built with Leaflet, Leaflet.markercluster, and Leaflet.heat.

## Copyright
© 2025 **Zheng Gang**. All rights reserved.  
Map data © OpenStreetMap contributors. Library copyrights belong to their respective owners.
