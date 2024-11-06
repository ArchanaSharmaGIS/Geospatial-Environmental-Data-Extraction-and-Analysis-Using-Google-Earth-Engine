
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
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [References](#references)

## Project Overview

This project provides an automated approach to extract geospatial environmental data using the Google Earth Engine API in Python. It includes multiple datasets such as NDVI, NDRE, NDMI, temperature, rainfall, slope, elevation, hillshade, and canopy height. The data can be used for a variety of applications including vegetation health monitoring, climate change research, land-use planning, and topographic analysis.

The project provides code in Jupyter Notebooks that can be easily modified to suit different geographic regions, time frames, and research needs. The extracted data is stored in formats that are easily downloadable and ready for further analysis.

## Features

- **NDVI, NDRE, NDMI Extraction**: Automatically extracts vegetation indices like NDVI, NDRE, and NDMI for vegetation health analysis.
- **Climate Data**: Retrieves temperature and rainfall data for climate monitoring.
- **Topographic Data**: Slope, elevation, and hillshade data for terrain analysis.
- **Canopy Height**: Extracts canopy height data for forest monitoring.
- **Time-Series Data**: Time-series analysis of NDVI, NDRE, NDMI, temperature, and rainfall data.
- **Data Download**: Ability to download processed data for further analysis.

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
