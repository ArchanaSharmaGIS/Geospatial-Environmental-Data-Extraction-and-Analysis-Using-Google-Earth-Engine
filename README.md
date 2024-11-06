
# Geospatial Environmental Data Extraction and Analysis Using Google Earth Engine (GEE)

This project uses the Google Earth Engine (GEE) API to extract, process, and analyze geospatial data for environmental monitoring. It includes vegetation indices (NDVI, NDRE, NDMI), temperature and rainfall data, topographic data (slope, elevation, hillshade), and canopy height data. Additionally, time-series data for NDVI, NDRE, NDMI, rainfall, and temperature is downloaded to support trend analysis and long-term studies.

## Features

- **Vegetation Indices**: NDVI, NDRE, NDMI calculations.
- **Meteorological Data**: Temperature and rainfall data extraction.
- **Topographic Data**: Slope, elevation, hillshade, and canopy height data.
- **Time-Series Data Extraction**: Monthly time-series data for NDVI, NDRE, NDMI, rainfall, and temperature.
- **Data Download Capability**: All extracted data is made available for download for further analysis.
  
## Requirements

- **Python 3.7+**
- **Google Earth Engine API**: To access and process geospatial data from Earth Engine.
- **GeoPandas**: For geospatial data handling in Python.
- **Other Libraries**: `numpy`, `pandas`, and `matplotlib` for data manipulation and visualization.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
