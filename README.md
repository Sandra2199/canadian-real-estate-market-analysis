# Canadian Real Estate Market Analysis

This project analyzes Canadian real estate market trends using Python and Tableau to identify pricing patterns, regional differences, and relationships between property characteristics and housing prices.

## Tools Used

- Python
- pandas
- matplotlib
- seaborn
- Tableau
- Google Colab

## Project Overview

This project explores Canadian real estate market trends using Python and Tableau. The analysis focuses on identifying pricing patterns, regional differences, and relationships between housing characteristics such as square footage, bedrooms, and location.

The project includes data cleaning, exploratory data analysis (EDA), and an interactive Tableau dashboard to support housing market insights and visualization.

## Dataset Information

The dataset contains Canadian real estate listings collected from Remax Canada and published on Kaggle.

### Features included:
- City
- Province
- Property Type
- Price
- Bedrooms
- Bathrooms
- Square Footage

### Data Source
- Source: Remax Canada
- Collection Date: February 16, 2025

## Key Insights

- British Columbia and Ontario showed the highest average housing prices among the provinces included in the analysis.
- Most properties were concentrated between 2 and 4 bedrooms, representing the largest share of the market inventory.
- Housing prices generally increased with larger square footage and higher bedroom counts.
- Most properties were concentrated within lower and moderate price-per-square-foot ranges, while premium properties extended the market toward significantly higher values.

## Dashboard Preview

![Dashboard Preview](dashboard_preview.png)

## Interactive Tableau Dashboard

[View the Tableau Dashboard Here](https://public.tableau.com/views/CanadianRealEstateMarketAnalysis_17794230751190/CanadianRealEstateMarketAnalysis?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Repository Structure

- `Canadian_Real_Estate_Market_Analysis.ipynb` → Python analysis notebook
- `cleaned_canadian_housing_analysis.csv` → Cleaned dataset used for Tableau
- `dashboard_preview.png` → Tableau dashboard screenshot

## Future Improvements

- Include time-series analysis for housing market trends over time.
- Explore neighbourhood-level pricing patterns.
- Add additional housing variables such as property age and amenities.
