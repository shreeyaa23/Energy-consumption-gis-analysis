# Tripura Energy Consumption GIS Analysis

## Overview
This project presents a district-wise analysis of electricity consumption across the Indian state of Tripura using both Python and R.  
It applies Geographic Information System (GIS) techniques through **GeoJSON-based spatial mapping** to visualize regional consumption patterns and disparities.

---

## Objectives
- Perform exploratory data analysis (EDA) on district-level electricity consumption data.
- Integrate geospatial data (GeoJSON) for district boundary mapping.
- Develop thematic visualizations (choropleth maps) to identify high and low consumption zones.
- Compare analytical workflows in Python and R for reproducibility and performance.

---

## Methodology

### Step 1: Data Preparation
- Imported district-wise consumption data from Excel.
- Loaded Tripura district boundaries from a GeoJSON file.
- Merged both datasets using district name as a spatial join key.

### Step 2: Visualization
- Created bar and histogram plots for initial insights.
- Generated **GIS-based maps** using GeoPandas (Python) and ggplot2 (R) to display energy consumption intensity by region.

### Step 3: Analysis
- Compared total, average, and relative consumption per district.
- Identified geographic trends in power usage and infrastructure needs.

---

## Key Insights
- **West Tripura** has the highest overall energy consumption, correlating with higher population density and urban infrastructure.
- **Dhalai and North Tripura** exhibit lower demand, suggesting rural consumption dominance.
- Spatial mapping highlights **clear east-west disparities** in electricity usage.

---

## Tools and Technologies
- **Python:** pandas, matplotlib, geopandas  
- **R:** ggplot2, sf  
- **Data Sources:**  
  - Tripura energy consumption dataset (Excel)  
  - District boundaries (`TRIPURA_DISTRICTS.geojson`)

---

