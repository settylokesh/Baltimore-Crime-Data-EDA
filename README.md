
# Baltimore Crime Analysis Project

This project analyzes Baltimore crime data to uncover significant trends, patterns, and insights. It integrates multiple datasets, performs comparisons across time periods, and visualizes changes in crime rates and related factors, providing actionable insights for policy-makers and law enforcement agencies.



## Table of Contents
- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Data Sources](#data-sources)
- [Methodology](#methodology)
  - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
  - [Final Analysis](#final-analysis)
- [Insights](#insights)
- [Visualizations](#visualizations)
- [How to Run the Project](#how-to-run-the-project)
- [Future Scope](#future-scope)

---

## Project Overview

This project focuses on identifying and analyzing crime trends in Baltimore, Maryland, from 2017 to 2022. By merging and comparing datasets across years, the analysis highlights changes in crime patterns, identifies high-risk neighborhoods, and explores relationships between various factors like vacant properties and gun-related offenses.

---

## Key Features

1. **Comprehensive Data Integration**:
   - Merges datasets for crime incidents, vacant notices, gun offenses, and vacant rehabs from 2017 and 2022.
   - Calculates differences and percentage changes to quantify trends.

2. **Descriptive and Comparative Analysis**:
   - Compares neighborhoods based on crime activity and related factors.
   - Identifies top- and bottom-performing neighborhoods in terms of crime reduction.

3. **Visual Insights**:
   - Generates heatmaps, scatter plots, and bar charts to illustrate trends and correlations.

4. **Correlation Analysis**:
   - Examines relationships between changes in crime rates and other socio-economic factors.

---

## Data Sources

The datasets used in this project include:
- **Crime Incidents**: Data on crime incidents, including type, time, and location.
- **Vacant Notices**: Information on vacant properties issued notices.
- **Gun Offenses**: Data on gun-related offenses.
- **Vacant Rehabs**: Details about properties undergoing rehabilitation.


The datasets used in this analysis are:

- [`Part_1_Crime_Data.csv`](https://bpdgis.maps.arcgis.com/apps/dashboards/511ba81db3414df3bb474749b69bc258): Crime statistics dataset.
- [`Vacant_Building_Notices.csv`](https://arcg.is/1TCH0D): Dataset for vacant building notices.
- [`Gun_Offenders_Registry.csv`](https://arcg.is/1K9fDH): Dataset for gun offenders registry.
- [`Vacant_Building_Rehabs.csv`](https://arcg.is/yvWeb): Dataset for vacant building rehabs.
---

## Methodology

### Exploratory Data Analysis (EDA)
1. **Initial Cleaning**:
   - Removed duplicates and handled missing values.
2. **Descriptive Statistics**:
   - Calculated crime frequencies and distributions.
3. **Visualization**:
   - Created heatmaps and line charts to identify temporal and spatial patterns.
4. **Grouping by Neighborhood**:
   - Aggregated data by neighborhood for year-wise comparisons.

### Final Analysis
1. **Data Merging**:
   - Merged 2017 and 2022 datasets for crime, vacant notices, gun offenders, and vacant rehabs.
   
2. **Calculations**:
   - Calculated differences and percentage changes in crime rates across years:
    
3. **Correlation Analysis**:
   - Examined relationships between changes in crime and other factors like vacant notices.

---



## How to Run the Project

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Run the Jupyter notebooks:
   ```bash
   jupyter notebook
   ```
3. Execute the cells sequentially to replicate the analysis.

---

## Future Scope

1. **Machine Learning**:
   - Predict crime rates based on historical data and socio-economic factors.
2. **Real-Time Data Integration**:
   - Incorporate live data feeds for up-to-date insights.
3. **Policy Recommendations**:
   - Translate insights into actionable strategies for law enforcement.



