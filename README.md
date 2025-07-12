# Daily_water_level_reservoirs_India

# 📊 Daily Reservoir Level Data (CWC) – March 2024

This repository contains the daily water reservoir level data provided by the **Central Water Commission (CWC)** for the month of **March 2024**. The dataset can support analysis related to hydrology, climate change, water resource planning, and geospatial visualization.

---

## 📁 Dataset Overview

- **File Name**: `Daily_data_of_reservoir_level_of_Central_Water_Commission_(CWC)_Agency_during_March_2024.csv`
- **Rows**: 3,689
- **Columns**: 13

---

## 🧾 Column Description

| Column Name            | Type         | Description                                 |
|------------------------|--------------|---------------------------------------------|
| `Reservoir_name`       | Categorical  | Name of the reservoir                       |
| `Basin`                | Categorical  | River basin in which the reservoir lies     |
| `Subbasin`             | Categorical  | Sub-basin name                              |
| `Agency_name`          | Categorical  | Reporting agency (CWC)                      |
| `Date`                 | Categorical  | Observation date                            |
| `Lat`                  | Continuous   | Latitude of reservoir                       |
| `Long`                 | Continuous   | Longitude of reservoir                      |
| `Year`                 | Continuous   | Year of observation                         |
| `Month`                | Continuous   | Month of observation                        |
| `Full_reservoir_level` | Continuous   | Maximum water level (meters)                |
| `Live_capacity_FRL`    | Continuous   | Live capacity at full reservoir level (MCM) |
| `Storage`              | Continuous   | Actual water stored (MCM)                   |
| `Level`                | Continuous   | Current water level (meters)                |

---

## 💡 Use Cases

This dataset can be used in various analytical and operational scenarios, such as:

### 🧪 Data Science & Machine Learning
- **Predictive Modeling**: Forecast future reservoir storage using historical water levels.
- **Time Series Analysis**: Identify trends, seasonality, and anomalies in reservoir levels.
- **Clustering**: Group reservoirs with similar characteristics or behavior patterns.

### 🌍 Geospatial Applications
- **Reservoir Mapping**: Visualize reservoir locations and water levels using `folium` or `geopandas`.
- **Regional Comparison**: Analyze basin-wise or state-wise water availability.

### 🚰 Water Resource Management
- **Drought Monitoring**: Track declining storage levels to identify drought-prone areas.
- **Supply-Demand Planning**: Assist state agencies in forecasting water needs vs availability.

### 📊 Dashboards & Reporting
- **Real-Time Monitoring**: Build dashboards for government/public awareness.
- **Alert Systems**: Set thresholds to issue alerts for low reservoir
