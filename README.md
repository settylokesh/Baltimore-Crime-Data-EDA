# Baltimore Crime Analysis

This project aims to analyze the relationship between various urban factors and crime rates in Baltimore. The analysis includes data cleaning, summarization, correlation analysis, and visualization to understand how factors like vacant building notices, gun offenders, and vacant building rehabs relate to crime rates.

## Project Structure

The project is organized into several sections, each focusing on different aspects of the analysis:

1. **Importing Libraries**: Import necessary libraries for data manipulation, visualization, and statistical analysis.
2. **Reading Data Sets**: Load datasets related to crime, vacant building notices, gun offenders, and vacant building rehabs.
3. **Data Cleaning**: Standardize date formats, handle missing values, and prepare data for analysis.
4. **Summarizing Data**: Summarize counts by neighborhood for the years 2017 and 2022.
5. **Calculating Percentage Change**: Calculate the difference and percentage change between 2017 and 2022 for each dataset.
6. **Sorting Percentage Change**: Sort neighborhoods based on percentage change for each dataset.
7. **Analyzing Correlation**: Analyze the correlation between changes in different factors and changes in crime rates.
8. **Pearson Correlation Test**: Perform Pearson correlation tests to determine the significance of the correlations.
9. **Visualizations**: Create visualizations to illustrate the findings, including bar charts, scatter plots, histograms, and heatmaps.
10. **Conclusion**: Summarize the results and provide insights based on the analysis.

## Data Sources

The datasets used in this analysis are:

- [`Part_1_Crime_Data.csv`](https://bpdgis.maps.arcgis.com/apps/dashboards/511ba81db3414df3bb474749b69bc258): Crime statistics dataset.
- [`Vacant_Building_Notices.csv`](https://arcg.is/1TCH0D): Dataset for vacant building notices.
- [`Gun_Offenders_Registry.csv`](https://arcg.is/1K9fDH): Dataset for gun offenders registry.
- [`Vacant_Building_Rehabs.csv`](https://arcg.is/yvWeb): Dataset for vacant building rehabs.

