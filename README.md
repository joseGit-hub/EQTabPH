# 🇵🇭 PHIVOLCS Philippine Earthquake & Seismic Analysis Dashboard (2016–2026)

<img width="1919" height="1048" alt="Dashboard_Preview" src="https://github.com/user-attachments/assets/3227fc68-4709-4b18-a191-b8c5893487cc" />

## Tech Stack

![TABLEAU](https://img.shields.io/badge/TABLEAU-E9762B?style=for-the-badge&logo=tableau&logoColor=white) ![EXCEL](https://img.shields.io/badge/EXCEL-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white) ![GIS](https://img.shields.io/badge/GIS-73B9BC?style=for-the-badge&logo=qgis&logoColor=white)

## Description

An interactive geospatial and statistical tool designed to monitor and analyze seismic events, magnitudes, and focal depths across the Philippines using PHIVOLCS records.

## How did I create it?

I first compiled real seismic records from PHIVOLCS into structured datasets. The data was cleaned and formatted with spatial coordinates (Latitude/Longitude), timestamps, specific locations, and focal depths, allowing for organized geospatial mapping.

Using earthquake performance and magnitude data from **2016 to 2026**, the application transforms raw government statistics into actionable insights for hazard identification and regional risk assessment.

## Key Features

### A. Geographic Seismic Map
* **Spatial Encodings:** Visualizes earthquake epicenters across the Philippines with **circle size and color intensity** dynamically scaling with **Magnitude** (`AVG(Magnitude)`).
* **Dark-Mode GIS Layer:** Implemented custom dark-mode satellite mapping layers to maximize the contrast of high-magnitude seismic events.

### B. Annual Magnitude Trends
* **Trend Breakdown:** Visualizes seismic shifts and average magnitude distributions across the 10-year span (2016–2026).

### C. Depth Distribution Analysis
* **Focal Depth Tracking:** Analyzes focal depth patterns over time to help distinguish shallow vs. deep seismic activity.

#### Data Reference
* https://www.kaggle.com/datasets/bwandowando/philippine-earthquakes-from-phivolcs
