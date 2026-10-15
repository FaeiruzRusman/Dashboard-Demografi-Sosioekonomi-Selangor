# SUO Demografi & Sosioekonomi — Fasa 1

Standalone static dashboard (index.html) for GitHub Pages. Six tabs: Executive Overview, Demography, Socioeconomics, District Benchmarking, Spatial Intelligence, Urban Intelligence. The first four tabs use official remote DOSM CSV feeds; Spatial Intelligence supports uploading official Selangor district GeoJSON (not embedded or invented); advanced indices are marked as pending.

## Official sources
- https://storage.dosm.gov.my/population/population_district.csv
- https://storage.dosm.gov.my/hies/hh_income_district.csv
- https://storage.dosm.gov.my/hies/hh_poverty_district.csv

All numbers depend on online retrieval from DOSM. Browser cross-origin rules may affect loading. Median household income and poverty rates must not be aggregated via simple sum/average of district values. Therefore statewide values are intentionally not shown for these metrics until proper state level sources are integrated. Population values reported in thousands are multiplied by 1,000 for display. Note published source update dates and district nomenclature when integrating an official GeoJSON.

## Run
Serve via a local HTTP server (e.g. `python -m http.server 8000`) or GitHub Pages; open `index.html`. Requires internet for Chart.js CDN and DOSM data feeds.