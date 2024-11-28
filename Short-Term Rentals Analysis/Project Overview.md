# Short-Term Rentals Analysis: Data Visualizations with Python and Tableau

## Project Overview
This project explores short-term rental data in Toronto to visualize key insights using both Python (with Matplotlib, Seaborn, Plotly) and Tableau Public. The visualizations highlight the distribution of rental properties across property types and wards, giving insights into geographic and property type patterns within the city. The data is sourced from Toronto's open dataset on short-term rentals.

## Table of Contents

1. [Data Analysis](#Data-Analysis)
2. [Python Visualization](#Python-Visualization)
3. [Tableau Dashboard](#Tableau-Dashboard)
4. [Summary](#Summary)

## Data Analysis

[Original Data Source](https://open.toronto.ca/dataset/short-term-rentals-registration/)

[Linked to raw and processed data folders]()

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

[Link for Python file]()

![output properties by type](https://github.com/user-attachments/assets/cf995935-4916-46e6-8ba2-aae20d867e00)

![output by ward](https://github.com/user-attachments/assets/7fe1e35b-1171-4c53-8c8d-cda6ad938752)

![output distribution](https://github.com/user-attachments/assets/956a4732-0489-44b3-8e22-8a70b1edc9e6)


## Tableau Dashboard

[Link for Tableau Dashboard](https://public.tableau.com/app/profile/n.y8309/viz/DashboardShort-TermRental/DashboardShort-TermRental?publish=yes)

![Short-Term Rental Properties by Type](https://github.com/user-attachments/assets/3eb6206d-127a-4d1c-9dec-e57f6055cbda)

![Short-Term Rental Properties by Ward](https://github.com/user-attachments/assets/16e503ff-7e78-47d3-b2db-d3a68e0125b0)

![Property Type Distribution by Ward](https://github.com/user-attachments/assets/d77d4932-2f83-4d0b-ba65-f1513ee8a1e6)


## Summary

### Short-Term Rentals by Property Type

As of recent data, there are a significant number of short-term rentals in the city, with residents and property owners utilizing platforms like Airbnb.

In Toronto, regulations require short-term rental operators to register their principal residences, including those in single-detached or semi-detached houses, as well as in condominiums. These rentals are allowed to be booked for less than 28 days, and there are restrictions on how frequently these properties can be rented out. For example, an entire house can be rented for up to 180 nights per year, while renting individual rooms has fewer restrictions on rental days​

Condos are a popular choice for short-term rentals in Toronto, with many listings found in downtown and central areas​. 3282 condominiums are listed in Toronto. However, some condominiums may have additional rules that limit or prohibit short-term rentals based on their own bylaw. In addition, there are 3743 single-semi detached houses listed for short-term rental in Toronto. These homes are also popular for short-term stays, often providing more space and privacy than condos. For entire house rentals, the city allows up to 180 nights of rental per year, with specific rules for registration and operation​.

### Short-Term Rentals by Ward

Spadina—Fort York, located in Toronto, is a popular ward that encompasses diverse neighborhoods, including those close to the waterfront and downtown areas. As a prime location, this ward sees a high concentration of short-term rental properties, with reports indicating that there are around 2,457 short-term rental listings in the area. 

In Spadina—Fort York, approximately 2,068 of the 2,457 short-term rental properties are condominiums. This highlights the area's popularity for condo-based rentals, which is consistent with the high density and demand for short-term accommodations in central Toronto. Condos are particularly sought after due to their proximity to downtown amenities, tourist attractions, and convenient public transit options

The Davenport ward in Toronto has the highest number of single-family detached properties among the city's wards, with approximately 359 properties (total properties for short-term rental). This is  significant in the context of Toronto's real estate landscape, as single-family detached homes are often in high demand due to their space, privacy, and typically larger lots compared to other property types, such as condominiums or townhouses.

Davenport is a diverse and vibrant area with a mix of residential housing, including single-family homes, as well as multi-family units and a variety of other property types, making it an attractive choice for both long-term residents and short-term renters. Properties in this ward benefit from proximity to major transportation routes, local amenities, and green spaces​.


