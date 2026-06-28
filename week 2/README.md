# Tesla EA Deliveries & Production ML Pipeline

This assignment builds an end-to-end machine learning workflow on Tesla deliveries and production data from 2015–2025.

## What’s included

- Data loading, inspection, cleaning, missing-value checks, and duplicate-row removal
- Exploratory data analysis with charts for deliveries by model, deliveries by region, correlation heatmap, production vs deliveries, and time trends
- Feature engineering with label encoding, lag features, rolling averages, and monthly aggregations
- Regression modelling with chronological 80/20 splitting, Linear Regression, Random Forest, cross-validation, and feature importance analysis
- Time series forecasting with SARIMA, Prophet, and Holt-Winters
- ADF stationarity testing and a final model comparison summary

## Main notebook

- [Week2_abhishek_upadhyay.ipynb](week2_abhishek_upadhyay.ipynb)

## Run order

1. Open the notebook in Jupyter or VS Code.
2. Run the cells from top to bottom.
3. Review the printed metrics, charts, and final conclusion at the end.

## Output notes

- The notebook uses the dataset `tesla_deliveries_dataset_2015_2025.csv` in the same folder.
- The strongest regression result in the current run is Linear Regression on the engineered feature set.
- Forecasting models are included for comparison, but the supervised regression models perform best on this dataset.
