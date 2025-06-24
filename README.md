# Disaster and Climate Analysis in Bangladesh (1990–2013)

## Overview
This project analyzes natural disasters, weather, and climate trends in Bangladesh from **1990 to 2013**.  Submitted for the **Data Visualization Competition at the 6th Bangladesh Economics Summit**, it uses compelling visualization story to explore:

- Disaster impacts
- Temperature anomalies
- Rainfall patterns
- Correlations between climate variables and natural disasters

---

## Purpose
- Examine disaster frequency, human toll, and economic damage
- Analyze long-term temperature and rainfall trends to detect climate change
- Explore links between climate variables and disasters (especially floods)
- Highlight regional climate variability and project future patterns

---

## Read the Visualization Story
Link: https://tinyurl.com/4cubbke5
---

## Datasets

### 1. `disaster_data_cleaned.csv`
- **Contents**: Disaster types, dates, death tolls, affected populations, and economic losses


### 2. `weather_data_1990_2020.csv`
- **Contents**: Monthly data on temperature, rainfall, wind speed, and station coordinates (1990–2020)


### 3. `bd_climate_1990-2013.csv`
- **Contents**: Monthly average temperature data for Bangladesh


---

## Dataset Sources
- Weather data: https://www.kaggle.com/datasets/emonreza/65-years-of-weather-data-bangladesh-preprocessed
- Disaster data: https://public.emdat.be/data
- Climate data: https://climateknowledgeportal.worldbank.org/

All of these datasets are public.

---

## Analysis & Methods

- **Libraries used**: `pandas`, `matplotlib`, `seaborn`, `statsmodels`, `scipy`
- **Key analysis steps**:
  - **Disaster Trends**: Bar plots, timeline charts, and heatmaps for frequency and severity
  - **Climate Trends**: Monthly anomalies, rainfall extremes, flood correlations
  - **Correlation Studies**: Heatmaps and scatter plots linking weather and disaster variables
  - **Prediction Models**: Logistic regression to predict flood likelihood based on rainfall and anomalies
  - **Regional Insights**: Geographic scatter plots and seasonal distribution patterns


