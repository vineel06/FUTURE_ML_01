# FUTURE_ML_01
# Sales & Demand Forecasting (Task 1)

## Overview
This project builds a sales forecasting system using historical retail sales data.
The goal is to predict future sales trends and present insights in a business-friendly way.

## Dataset
Superstore Sales Dataset (Kaggle)  
https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

## Approach
1. Loaded and cleaned historical sales data
2. Converted order dates into time-based features (day, month, year)
3. Aggregated data to daily total sales
4. Trained a Linear Regression model for forecasting
5. Evaluated performance using MAE and RMSE
6. Forecasted sales for the next 30 days
7. Visualized historical, predicted, and forecasted sales

## Results
- The model captures overall sales trends over time
- Forecasted sales provide an estimate of expected demand for the next month

## Business Use Case
This forecast can help businesses:
- Plan inventory and restocking
- Avoid overstocking or shortages
- Prepare staffing based on expected demand
- Support short-term sales planning decisions

## Tools Used
- Python
- Pandas, NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook
