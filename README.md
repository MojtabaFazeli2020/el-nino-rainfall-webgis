# Interactive El Niño Rainfall Web GIS — 2024

Interactive Web GIS for visualizing El Niño–related rainfall using GPM data, GIS, and deck.gl.

## Project workflow

GPM IMERG → Google Earth Engine → rainfall analysis → processed data → deck.gl → Interactive Web GIS

## Repository structure

```text
el-nino-rainfall-webgis/
├── data/
│   ├── raw/          # Original downloaded/exported datasets
│   ├── processed/    # Processed rainfall datasets
│   └── geojson/      # Vector data for Web GIS
├── gee/              # Google Earth Engine scripts
├── python/           # Python data processing and analysis
├── qgis/             # QGIS projects, styles, and GIS processing
├── web/
│   ├── src/          # Web GIS source code
│   └── public/       # Static web assets
├── results/          # Maps, figures, and final outputs
├── docs/             # Documentation
└── README.md
```

## Study area

Rio Grande do Sul, southern Brazil.

## Main technologies

- Google Earth Engine
- GPM IMERG
- Python
- QGIS
- GeoJSON
- deck.gl
- Web GIS

## Project goal

Develop an interactive rainfall visualization for the 2024 El Niño period, with spatial rainfall intensity, temporal exploration, and interactive map-based data inspection.
