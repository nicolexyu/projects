# Short-Term Rentals Analysis: Data Visualizations with Python and Tableau

## Project Overview
This project explores short-term rental data in Toronto to visualize key insights using both Python (with Matplotlib, Seaborn, Plotly) and Tableau Public. The visualizations highlight the distribution of rental properties across property types and wards, giving insights into geographic and property type patterns within the city. The data is sourced from Toronto's open dataset on short-term rentals.

## Table of Contents

1. [Data Analysis](#Data-Analysis)
2. [Python Visualization](#Python-Visualization)
3. [Tableau Dashboard](#Tableau-Dashboard)
4. [Summary](#Summary)

## Data Analysis

[Data Source]([https://open.toronto.ca/dataset/short-term-rentals-registration/])

### Data Cleaning and Missing Values Handling

This cleaning process ensures the dataset is prepared for accurate and reliable visualizations while adhering to the stated analytical objectives.

1. Initial Check for Missing Values:
   
A preliminary inspection of the dataset revealed missing values in the following columns:
   - unit: 3,795 missing values (not critical for analysis).
   - ward_number: 4 missing values (critical for analysis but very small in proportion to the dataset size).
   - ward_name: 4 missing values (critical for analysis but very small in proportion to the dataset size).

All other columns were complete with no missing data.

2. Handling Missing Values:

Unit Column: Missing values in the unit column were left as is since the absence of unit numbers does not affect the analysis of property types or ward distributions.

Ward Number and Ward Name Columns: Rows with missing values in these critical columns were dropped to maintain data quality for analyses and visualizations involving geographic or ward-based attributes. Since there were only 4 missing values, this represents a negligible portion of the dataset and does not impact the overall analysis.

## Python Visualization


## Tableau Dashboard


## Summary

