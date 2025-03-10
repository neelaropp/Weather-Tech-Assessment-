# Weather Trend Forecasting - Advanced Analysis

## Project Overview
This project aims to analyze and forecast global weather trends using the **Global Weather Repository** dataset. The analysis includes **data cleaning, anomaly detection, multiple forecasting models, climate analysis, environmental impact study, and spatial analysis** to understand weather patterns and their impact.

## Dataset
- **Source**: Kaggle - Global Weather Repository
- **Features**: Contains over **40 attributes** including temperature, wind speed, humidity, precipitation, air quality measures, and geographical data.

## Steps & Methods Used

### 1. Data Cleaning & Preprocessing
- Converted timestamps to **datetime format**.
- Removed redundant and unnecessary columns.
- Handled outliers in **wind speed** and **air quality indicators**.
- Applied **Min-Max Normalization** to scale temperature, humidity, and other numerical features.
- Set **time-based indexing** for time series analysis.

### 2. Exploratory Data Analysis (EDA)
- **Visualized temperature and precipitation trends** over time.
- **Identified anomalies** using statistical outlier detection.
- Conducted a **seasonal temperature analysis** by month.

### 3. Forecasting with Multiple Models
- **ARIMA Model**: Used for short-term temperature forecasting.
- **Random Forest Regressor**: Applied for predictive modeling based on multiple weather variables.
- **Comparison of Forecasts**: Visualized the difference in predictions between ARIMA and Random Forest models.

### 4. Advanced Analyses
#### **Climate Analysis**
- Studied **long-term temperature trends** and seasonal variations.
- Analyzed **monthly temperature fluctuations** to understand climate shifts.

#### **Environmental Impact Analysis**
- Conducted **correlation analysis** between air quality indicators and weather parameters.
- Generated a **heatmap** to highlight key relationships between weather attributes.

#### **Spatial Analysis**
- Mapped the **geographical distribution** of weather data.
- Used **Geopandas** to overlay weather data on a world map to visualize climate variations across countries and continents.

## Results & Insights
- **Temperature forecasting** with ARIMA and Random Forest provides reliable trends for short-term predictions.
- **Anomaly detection** highlighted extreme temperature events, which could be crucial for climate change monitoring.
- **Air quality correlation** shows that pollution levels significantly impact weather conditions, reinforcing the importance of environmental policies.
- **Spatial patterns** reveal significant regional variations in temperature and climate conditions, supporting the need for localized climate adaptation strategies.

## Deliverables
- **Jupyter Notebook** with all analyses and visualizations.
- **Presentation-ready figures** showcasing trends, forecasts, and insights.
- **Github repository/project folder** containing:
  - Python scripts
  - Dataset (or reference to Kaggle dataset)
  - README documentation

## Future Improvements
- Incorporate **deep learning models** (LSTMs) for more complex forecasting.
- Perform **geospatial clustering** to identify regions with similar climate conditions.
- Develop an **interactive dashboard** for real-time weather analysis and predictions.

---
**Author**: Neela Ropp  
**Date**: March 2025  
**Tools Used**: Python, Pandas, Matplotlib, Seaborn, ARIMA, Random Forest, Geopandas, Scikit-learn  

