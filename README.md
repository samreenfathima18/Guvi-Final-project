# Enterprise Retail Intelligence: Multi-Level Demand Forecasting and Inventory Optimization

## Project Overview

Enterprise Retail Intelligence is an end-to-end demand forecasting and inventory optimization system developed using the M5 Forecasting Competition dataset. The project predicts future retail demand using machine learning and deep learning models and generates inventory recommendations to support better retail decision-making.

## Objectives

* Forecast retail demand across multiple products and stores.
* Compare multiple forecasting models.
* Optimize inventory using predicted demand.
* Build an interactive Streamlit dashboard.
* Support data-driven retail decision-making.

## Dataset

**Source:** M5 Forecasting Competition Dataset

### Files Used

* sales_train_validation.csv
* calendar.csv
* sell_prices.csv

### Dataset Summary

* 30,490 Products
* 10 Stores
* 3 States
* 42,840 Hierarchical Time Series

## Project Workflow

1. Data Cleaning
2. Exploratory Data Analysis
3. Data Preprocessing
4. Feature Engineering
5. Model Development
6. Model Evaluation
7. Inventory Optimization
8. Streamlit Dashboard

## Models Implemented

* Linear Regression
* CatBoost
* XGBoost
* LightGBM
* Enterprise LSTM

## Model Performance

| Model             |        MAE |       RMSE |      MAPE |         R² |
| ----------------- | ---------: | ---------: | --------: | ---------: |
| Linear Regression |     1.0538 |     2.1349 |     59.38 |     0.6367 |
| CatBoost          |     1.0207 |     2.0395 |     57.74 |     0.6685 |
| XGBoost           |     1.0158 |     2.0448 |     57.55 |     0.6667 |
| **LightGBM**      | **1.0132** | **2.0249** | **57.33** | **0.6732** |
| Enterprise LSTM   |     2.0594 |     4.2932 |    130.90 |     0.5802 |

## Best Model

**LightGBM** achieved the best performance and was selected for the inventory recommendation engine.

## Business Features

* Demand Forecasting
* Inventory Optimization
* Restock Recommendations
* Model Comparison
* Business Insights Dashboard

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* LightGBM
* XGBoost
* CatBoost
* TensorFlow / Keras
* Streamlit
* Google Colab

## Project Structure

```text
Enterprise_Retail_Intelligence/
│
├── notebooks/
├── models/
├── prepared_data/
├── outputs/
├── results/
├── streamlit/
├── README.md
└── requirements.txt
```

## Author

**S. Samreen Fathima**

Course: Data Science
