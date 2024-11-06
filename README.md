
# Geospatial Environmental Data Extraction and Analysis Using Google Earth Engine (GEE)

This project leverages Python and the Google Earth Engine (GEE) API to extract and analyze a variety of environmental datasets. It includes key environmental indices like NDVI, NDRE, NDMI, climatic data (temperature, rainfall), topographic features (slope, elevation, hillshade), and canopy height data. The project is implemented entirely in Jupyter Notebooks, providing a streamlined approach for environmental monitoring, vegetation health analysis, and climate studies.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Prerequisites](#prerequisites)
- [Directory Structure](#directory-structure)
- [Data Sources](#data-sources)
- [Example Output](#example-output)
- [Contributing](#contributing)
-

## Project Overview

This project provides an automated approach to extract geospatial environmental data using the Google Earth Engine API in Python. It includes multiple datasets such as NDVI, NDRE, NDMI, temperature, rainfall, slope, elevation, hillshade, and canopy height. The data can be used for a variety of applications including vegetation health monitoring, climate change research, land-use planning, and topographic analysis.

The project provides code in Jupyter Notebooks that can be easily modified to suit different geographic regions, time frames, and research needs. The extracted data is stored in formats that are easily downloadable and ready for further analysis.

## Features
#### 1. Vegetation Indices
**NDVI (Normalized Difference Vegetation Index):** NDVI is widely used to monitor vegetation health, assessing green vegetation and its seasonal variation.<br>
**NDRE (Normalized Difference Red Edge Index):** NDRE is particularly sensitive to the chlorophyll content in vegetation, making it valuable for vegetation stress analysis.<br>
**NDMI (Normalized Difference Moisture Index):** NDMI is used to assess moisture content in vegetation and is helpful for drought monitoring and water stress analysis.<br>
#### 2. Meteorological Data
**Temperature:** This dataset provides monthly temperature data, useful for studying climate trends and the effect of temperature on vegetation health.<br>
**Rainfall:** Monthly rainfall data is essential for understanding precipitation patterns, which play a crucial role in crop and forest health.<br>
#### 3. Topographic Data
**Slope:** The slope dataset provides information on terrain steepness, useful for erosion modeling and agricultural planning.<br>
**Elevation:** Elevation data helps in understanding the landscape’s vertical features and influences on vegetation distribution and climate.<br>
**Hillshade:** This dataset simulates the effect of sun angles on the terrain, providing 3D visualization of topographic features.<br>
#### 4. Canopy Height
Canopy height data is extracted to understand forest structure and biomass. This information is vital for forest management and carbon modeling.
#### 5. Time-Series Data Extraction
NDVI, NDRE, NDMI, Rainfall, and Temperature: Monthly time-series data extraction allows the monitoring of trends in vegetation, climatic conditions, and their interrelationships over time.
#### 6. Data Download
The project enables users to download processed environmental data for further analysis or reporting.


## Installation

To get started with this project, you'll need to install Python and the required libraries. Here's how to set up the environment:

### Prerequisites

- Python 3.x
- Google Earth Engine Account
- Jupyter Notebook or Jupyter Lab

### Steps

1. Install required Python libraries:

```bash
pip install google-earth-engine
pip install geopandas
pip install numpy
pip install pandas
pip install folium
pip install matplotlib
pip install rasterio
pip install geemap
