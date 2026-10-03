# CCTV Equipment Demand Forecasting and Inventory Management System

## Project Overview

This project develops a demand forecasting and inventory management system for CCTV equipment. Historical CCTV sales data is analyzed using time-series forecasting techniques to predict future demand and support inventory planning.

## Objectives

- Analyze historical CCTV equipment demand.
- Identify demand trends and monthly patterns.
- Forecast future CCTV demand.
- Compare ARIMA and SARIMA forecasting models.
- Calculate safety stock and recommended inventory levels.
- Support data-driven inventory planning.

## Products

The dataset contains the following CCTV products:

- 2MP CCTV Camera
- 5MP CCTV Camera
- IP Camera
- DVR 8 Channel
- NVR 8 Channel
- 1TB Hard Disk
- Power Supply
- Network Switch
- CCTV Cable

## Dataset

The dataset contains:

- Date
- Product
- Units_Sold
- Support_Requests

The data covers the period from 2022 to 2025.

The dataset is simulated for academic/project purposes.

## Technologies Used

- Python
- Jupyter Notebook
- Anaconda
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Statsmodels

## Forecasting Models

### ARIMA

ARIMA was used as a baseline time-series forecasting model.

### SARIMA

SARIMA was used to incorporate seasonal time-series behavior.

## Model Evaluation

The models were evaluated using:

- MAE — Mean Absolute Error
- RMSE — Root Mean Squared Error
- MAPE — Mean Absolute Percentage Error

## Inventory Management

The system calculates:

- Predicted demand
- Safety stock
- Recommended stock

A safety-stock factor of 10% of predicted/average demand was used for this project.

## Project Outputs

### Data

- cctv_demand_data.csv
- forecast_2026.csv
- inventory_recommendation_2026.csv
- product_inventory_recommendation.csv
- final_project_summary.csv

### Models

- arima_model.pkl
- sarima_model.pkl

### Graphs

- forecast_2026.png
- model_comparison.png
- monthly_demand_trend.png
- monthly_seasonality.png
- product_demand.png
- product_inventory.png

## Conclusion

The project demonstrates how time-series forecasting and inventory analysis can be combined to support CCTV equipment demand planning. The system provides future demand estimates and inventory recommendations based on historical data.