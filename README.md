# Syria Population Analysis

Population analysis workflows for Syria using Python, Folium, and open-source geospatial datasets.

## Contents

### 05 Population Density Map

Population density visualisation using WorldPop population raster data.

Features:

- WorldPop 2026 population raster
- Population density visualisation
- Raster normalisation
- Custom colour ramp
- Folium ImageOverlay

---

### 06 Syria Windowed Reading Map

Efficient raster processing using Rasterio windowed reading.

Features:

- Windowed raster extraction
- Reduced memory usage
- Raster subset visualisation
- Folium ImageOverlay

---

### 07 Syria Zonal Statistics Map

Population estimation by governorate using zonal statistics.

Features:

- Governorate polygon selection
- Raster-vector analysis
- Population aggregation
- Representative point generation
- Proportional symbol map

---

### 08 Syria Idleb Population Mask Map

Population raster extraction for Idleb governorate.

Features:

- Polygon masking
- GeoTIFF generation
- Log transformation
- Raster normalisation
- ImageOverlay visualisation

---

## Data Sources

### Administrative Boundaries

- HDX OCHA
- Syrian Arab Republic – Subnational Administrative Boundaries

### Population Raster

- WorldPop
- Syrian Arab Republic 100m Population 2026

### Basemaps

- CARTO Light No Labels
- CARTO Dark Matter
- Esri World Imagery
- Esri World Terrain Base

---

## Tools

- Python
- GeoPandas
- Rasterio
- NumPy
- Matplotlib
- Folium

---

## Techniques Demonstrated

- Raster visualisation
- Raster normalisation
- Windowed reading
- Raster masking
- Zonal statistics
- GeoTIFF generation
- Log transformation
- ImageOverlay rendering
- Proportional symbol mapping
