# Satellite Explorer

A lightweight, web-based geospatial tool for exploring satellite imagery, defining Areas of Interest (AOIs), and exporting geographic data. It is designed to assist developers, researchers, and analysts in geographic research—such as identifying unmet business demand, analyzing regional hotspots, or scoping areas for data extraction.

## Features

- **High-Resolution Satellite Imagery:** View beautiful, high-quality satellite maps using the Stadia Maps API.
- **Interactive Drawing Tools:** Place markers, draw lines, and define custom polygons directly on the map.
- **Automatic Measurements:** Instantly calculates distances for lines and areas for polygons.
- **Seamless Data Export:** Export drawn features to KML and KMZ formats for immediate integration with other GIS tools (like Google Earth, QGIS, or custom data pipelines).

## Why This Exists?

While there are many powerful GIS tools (like QGIS, ArcGIS, or Google Earth) and web-based mapping utilities (like geojson.io), they often fall into one of two extremes:
1. **Too complex:** Traditional desktop GIS applications have steep learning curves, require installation, and can be overkill for simple Area of Interest (AOI) definitions.
2. **Too generic:** Lightweight web tools often lack high-resolution satellite defaults or aren't tailored for market research workflows.

**Satellite Explorer** bridges this gap. It provides a zero-setup, hyper-focused tool that runs purely in the browser. It is specifically designed to act as the lightweight "first step" in a larger geographic research pipeline—allowing analysts to quickly survey a region, define boundaries, and export them for downstream POI data extraction without unnecessary bloat.

## Getting Started

1. Clone or download this repository.
2. Open `satellite-explorer.html` in any modern web browser (no build process required).
3. (Optional) Paste your Stadia Maps API key in the sidebar to activate live satellite imagery. 
4. Use the toolbar to draw your regions of interest and export them!

## Common Use Cases

- **Market Research:** Identifying geographic gaps in business demand by scoping areas to analyze Points of Interest (POIs).
- **Urban Planning:** Defining emerging urban hotspots or underpopulated areas for development planning.
- **Data Pipelines:** Establishing search boundaries (AOIs) for fetching OpenStreetMap (OSM) or Overture Maps data downstream.

## Roadmap / To Do

- [ ] Add support for alternative map tile providers (e.g., Mapbox, Google Maps, OpenStreetMap).
- [ ] Implement automatic isochrone generation (travel time polygons) from a starting point.
- [ ] Integrate automated Point of Interest (POI) data fetching within drawn AOIs.
- [ ] Add the ability to save, import, and load project states locally.