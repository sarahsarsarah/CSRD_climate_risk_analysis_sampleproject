# CSRD Physical Climate Risk Analysis: Sample Project

A end-to-end geospatial climate risk assessment built in Python, using dummy data
so anyone can clone it and run it immediately.

The notebook walks through the full pipeline: loading asset locations, overlaying
flood and drought hazard zones, applying IPCC AR6 scenario scaling, classifying
risk tiers, and producing client-ready outputs including an interactive map and
summary tables.

---

## What this project covers

- Building and projecting a GeoDataFrame of asset locations (GeoPandas)
- Constructing synthetic flood and drought hazard zones as spatial polygons
- Spatial join between assets and hazard zones using `gpd.sjoin()`
- 1km buffer analysis to measure neighbourhood flood exposure
- Forward-looking hazard scores under SSP2-4.5 and SSP5-8.5 (IPCC AR6)
- Risk tier classification aligned with CSRD double materiality lan
