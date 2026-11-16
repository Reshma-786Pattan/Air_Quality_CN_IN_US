# Air Quality Analysis – India, China and USA (2014–2022)

## 1. Introduction

Air pollution is one of the major environmental challenges affecting countries worldwide. It occurs when harmful substances such as particulate matter and gaseous pollutants are released into the atmosphere, affecting environmental quality.

Air quality monitoring stations collect measurements of different pollutants to understand atmospheric conditions and monitor pollution levels.

This project focuses on analyzing historical air quality data from India, China and the United States between 2014 and 2022. The dataset contains observations collected from multiple monitoring stations and data sources across different geographical locations.

The project uses Python, Pandas, NumPy, Matplotlib and Seaborn to clean, explore, analyze and visualize air quality data.

## 2. Theoretical Background

Air quality analysis involves studying the concentration and distribution of pollutants in the atmosphere. Different pollutants have different characteristics, sources and measurement units.

The major pollutants considered in this project are:

### Particulate Matter

**PM2.5:** Fine particulate matter with a diameter of 2.5 micrometers or smaller. These particles can remain suspended in the atmosphere and are an important indicator of air pollution.

**PM10:** Particulate matter with a diameter of 10 micrometers or smaller. It includes dust, smoke and other airborne particles.

### Gaseous Pollutants

**Carbon Monoxide (CO):** A colorless and odorless gas produced mainly through incomplete combustion of carbon-containing fuels.

**Nitrogen Dioxide (NO₂):** A gaseous pollutant commonly associated with vehicle emissions, industrial activities and fuel combustion.

**Sulfur Dioxide (SO₂):** A gas mainly released through burning sulfur-containing fuels and certain industrial processes.

**Ozone (O₃):** Ground-level ozone is a secondary air pollutant formed through chemical reactions involving nitrogen oxides and volatile organic compounds in sunlight.

**Black Carbon (BC):** A component of particulate matter produced by incomplete combustion of fossil fuels and biomass.

## 3. Importance of Air Quality Analysis

Air quality analysis helps to:

- Understand the distribution of different pollutants.
- Compare recorded pollution levels across countries.
- Identify geographical variations in monitoring observations.
- Examine changes in pollutant concentrations over time.
- Understand seasonal and monthly pollution patterns.
- Identify locations with relatively higher recorded pollutant concentrations.
- Support environmental monitoring and data-driven decision-making.

## 4. Dataset Description

The dataset contains approximately 2 million air quality observations from India, China and the USA, covering the period from 2014 to 2022.

It includes the following variables:

| Variable | Description |
|---|---|
| location | Monitoring station name |
| area_name | City or geographical area |
| country | Country associated with the observation |
| pollutant | Type of air pollutant |
| value | Recorded pollutant measurement |
| timestamp | Date and time of observation |
| unit | Measurement unit |
| source_name | Data provider or monitoring source |
| averaged_over_in_hours | Averaging period of the measurement |
| latitude | Geographic latitude |
| longitude | Geographic longitude |
| location_geom | Geographic point representation |

## 5. Measurement Units

The dataset contains different measurement units, including:

- **µg/m³:** Micrograms per cubic metre, commonly used for particulate matter and other pollutant concentrations.
- **ppm:** Parts per million, used to express the concentration of gases.

Measurements must be compared carefully because different pollutants and units are not directly interchangeable.

## 6. Exploratory Data Analysis

Exploratory Data Analysis (EDA) is used to understand the structure, distribution and relationships within the dataset.

The project includes three major types of analysis:

### Univariate Analysis
Studies individual variables using:
- Histograms
- Box plots
- Count plots
- Bar charts
- Distribution plots

### Bivariate Analysis
Studies relationships between two variables using:
- Scatter plots
- Box plots
- Line charts
- Grouped bar charts
- Heatmaps

### Multivariate Analysis
Studies relationships among multiple variables using:
- Correlation heatmaps
- Faceted visualizations
- Multivariable comparisons
- Geographical visualizations
- Time-series comparisons

## 7. Expected Outcomes

The project aims to generate meaningful insights into historical air quality observations, including country-wise comparisons, pollutant distributions, temporal patterns, geographical variations and monitoring-source contributions.

The final outcome will be a collection of analytical visualizations and an interactive dashboard presenting the major findings of the study.

## 8. Conclusion

This project demonstrates how data analytics techniques can be applied to a large-scale environmental dataset to understand historical air quality observations.

By combining data cleaning, exploratory analysis and visualization, the project aims to transform raw monitoring records into understandable information that can support environmental analysis and informed decision-making.
