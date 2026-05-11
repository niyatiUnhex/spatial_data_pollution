# spatial_data_pollution

# Spatial Data Pollution Analysis

A comprehensive spatial and spatio-temporal data analysis project focused on air pollution patterns across Indian cities using statistical modeling, spatial econometrics, and geospatial visualization techniques.

## Project Overview

This project analyzes air pollution data (primarily PM2.5/AQI) to identify spatial dependence, regional clustering, and pollution hotspots. The study applies exploratory spatial data analysis (ESDA), interpolation methods, and spatial regression models to understand geographic pollution patterns and their temporal behavior.

## Objectives

- Analyze spatial distribution of air pollution levels across cities
- Detect pollution hotspots and coldspots
- Measure spatial autocorrelation in pollution data
- Build spatial regression models to capture neighborhood effects
- Generate interactive maps and visual insights for decision-making

## Methodology

### Exploratory Spatial Data Analysis (ESDA)
- Global Moran’s I
- Local Moran’s I (LISA)
- Spatial weights matrix construction
- Cluster and outlier analysis

### Spatial Interpolation
- Ordinary Kriging
- Variogram modeling
- Prediction surface generation

### Spatial Econometric Models
- Spatial Lag Model (SAR)
- Spatial Error Model (SEM)
- Maximum Likelihood estimation

### Visualization
- Choropleth maps
- LISA cluster maps
- Kriging prediction maps
- Interactive Folium maps

## Tools & Technologies

- **Python**
  - pandas
  - numpy
  - geopandas
  - matplotlib
  - folium



- **Jupyter Notebook / Google Colab**

## Project Structure

```bash
spatial_data_pollution/
│
├── data/                     # Raw and processed datasets
├── notebooks/                # Analysis notebooks
├── maps/                     # Generated spatial maps and outputs
├── reports/                  # Final report/presentation
├── scripts/                  # Utility scripts
└── README.md
```

## Key Insights

- Significant spatial autocorrelation observed in pollution levels
- High-high pollution clusters identified in major urban regions
- Kriging interpolation revealed strong regional pollution gradients
- Spatial lag effects indicate neighboring cities influence local pollution levels

## Applications

- Environmental monitoring
- Urban planning
- Public health risk assessment
- Policy decision support for pollution control

## Author

**Niyati Sharma**  
M.Sc. Statistics | Data Science & Spatial Analytics Enthusiast  

GitHub: https://github.com/niyatiUnhex
