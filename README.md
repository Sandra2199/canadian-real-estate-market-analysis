# Canadian Real Estate Listing Analysis

Cross-sectional analysis of Canadian residential property listings, focused on regional price comparisons, property characteristics, and visual market reporting.

## Quick Access

- [Analysis notebook](Canadian_Real_Estate_Market_Analysis.ipynb)
- [Processed analytical dataset](cleaned_canadian_housing_analysis.csv)
- [Interactive Tableau dashboard](https://public.tableau.com/views/CanadianRealEstateMarketAnalysis_17794230751190/CanadianRealEstateMarketAnalysis?:language=en-US&:display_count=n&:origin=viz_share_link)
- [Dashboard preview](dashboard_preview.png)

## Executive Summary

This project examines 42,509 processed Canadian residential listing records to compare asking prices, listing mix, and regional variation within a single-date market snapshot.

British Columbia and Ontario had the highest average listing prices among the 11 provinces and territories represented, and listings with two to four bedrooms accounted for **72.7%** of the processed records. The analysis also found that asking prices generally increased with bedrooms and square footage, while price per square foot had a right-skewed distribution.

The project demonstrates how descriptive analysis and Tableau reporting can organize market information while keeping listing volume, geographic coverage, and data limitations visible.

## Analytical Context

The analysis addresses:

> How do listing prices and property characteristics vary across the Canadian locations represented in the dataset, and which patterns are most useful for market reporting?

It focuses on:

- average listing prices by province and city;
- listing volume by bedroom count;
- relationships among price, square footage, and bedrooms;
- price-per-square-foot distributions; and
- interactive regional and property-level comparisons.

## Dataset and Analytical Scope

The notebook describes the source as a Kaggle dataset compiled from RE/MAX Canada listings and collected on February 16, 2025. The original source URL and licensing terms are not stored in this repository.

| Stage | Scope |
|---|---:|
| Source data loaded by the notebook | 44,787 records × 23 fields |
| Analytical dataset after documented filters | 42,509 listing records × 7 selected fields |
| Tableau-ready export | 42,509 records × 10 fields, including derived measures |

The analytical fields are city, province, listing price, bedrooms, bathrooms, property type, and square footage. Derived fields include price in millions, a combined city–province label, and price per square foot.

## Analytical Approach

1. Loaded and profiled the source listing data.
2. Selected property and location fields relevant to comparative reporting.
3. Applied project-defined validity filters for price, bedrooms, bathrooms, and square footage.
4. Created price and price-per-square-foot measures.
5. Compared listing prices and volumes across property sizes and locations.
6. Exported the processed analytical dataset for Tableau reporting.

## Key Results

- **British Columbia and Ontario had the highest average listing prices** among the 11 provinces and territories represented after the notebook's filters.
- **Listings with two to four bedrooms represented 72.7%** of the processed analytical records.
- **Average listing price generally increased with bedroom count**, while the square-footage analysis showed a positive relationship between property size and price.
- **Price per square foot was right-skewed**, with most records concentrated below the premium tail.
- British Columbia accounted for more than half of the processed records, so provincial averages need to be interpreted alongside listing counts.

These findings describe the records analyzed; they are not official Canadian market estimates or evidence of price changes over time.

## Market Insights

- Regional averages identify where listed properties were more expensive within this dataset.
- Bedroom and square-footage comparisons provide context for how property size relates to asking price.
- Listing counts are necessary alongside averages because geographic and property-type coverage varies substantially.
- Price per square foot provides a normalized comparison, but it still depends on property mix and local coverage.

## Dashboard

[Open the interactive Tableau dashboard](https://public.tableau.com/views/CanadianRealEstateMarketAnalysis_17794230751190/CanadianRealEstateMarketAnalysis?:language=en-US&:display_count=n&:origin=viz_share_link)

![Canadian Real Estate Market Analysis dashboard](dashboard_preview.png)

The dashboard presents the current training-project analysis and should be read with the data limitations below.

## Limitations

- The data is a **single-date listing snapshot**, so the project evaluates cross-sectional patterns rather than market trends over time.
- Dataset coverage is not demonstrated to be representative of the full Canadian housing market.
- The notebook detected duplicate records but did not establish their provenance or remove them; results therefore describe the processed dataset as implemented.
- City-level averages can be based on very small samples and should not be used as rankings without volume context.
- Project-defined cleaning rules require source-level validation before external benchmarking.
- The repository does not retain the original raw CSV, source URL, or licensing documentation, limiting full reproducibility and provenance verification.

## Deliverables

- [Jupyter notebook](Canadian_Real_Estate_Market_Analysis.ipynb) — data preparation, exploratory analysis, and visualizations
- [Processed analytical dataset](cleaned_canadian_housing_analysis.csv) — export used for reporting
- [Tableau dashboard](https://public.tableau.com/views/CanadianRealEstateMarketAnalysis_17794230751190/CanadianRealEstateMarketAnalysis?:language=en-US&:display_count=n&:origin=viz_share_link) — interactive presentation
- [Dashboard preview](dashboard_preview.png) — repository image of the published dashboard

## Tools and Methods

**Tools**

- Python: pandas, NumPy
- Matplotlib, Seaborn
- Tableau

**Methods**

- Data profiling and filtering
- Derived metric creation
- Grouped comparisons
- Distribution analysis
- Descriptive market reporting

## How to Explore

1. Review this README for the analytical scope and key findings.
2. Open the [analysis notebook](Canadian_Real_Estate_Market_Analysis.ipynb) for the preparation steps and visual analysis.
3. Explore the [Tableau dashboard](https://public.tableau.com/views/CanadianRealEstateMarketAnalysis_17794230751190/CanadianRealEstateMarketAnalysis?:language=en-US&:display_count=n&:origin=viz_share_link) for interactive comparisons.
4. Use the [processed dataset](cleaned_canadian_housing_analysis.csv) to inspect the current analytical output.

To reproduce the full cleaning workflow, replace the notebook's Google Drive source path with the location of an authorized copy of the original raw dataset.

## Project Context

This project was completed as part of the TripleTen Data Analyst training program. It applies exploratory data analysis and Tableau visualization to a Canadian real estate listing snapshot and is presented as descriptive market reporting rather than professional real estate advice or forecasting.

---

**Sandra Quinones**  
Business & Operations | Reporting & Data Analysis
