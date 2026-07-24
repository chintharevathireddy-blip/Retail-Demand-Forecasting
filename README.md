# Retail Demand Forecasting & Inventory Optimization

## Project Overview

This project predicts future retail product demand using historical sales data from the M5 Forecasting Dataset.

The objective is to help retail businesses maintain optimal inventory levels, reduce stockouts, and minimize overstock situations through machine learning.

The project includes:

- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- Machine Learning Model
- Sales Prediction
- Inventory Recommendation
- Model Evaluation

## Dataset

Dataset: M5 Forecasting Dataset (Walmart Sales)

Files Used:

- calendar.csv
- sell_prices.csv
- sales_train_validation.csv

The dataset contains historical daily sales, calendar information, promotional events, and product prices across multiple Walmart stores.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Jupyter Notebook
- Git & GitHub

## Project Structure

Retail-Demand-Forecasting/

├── data/
├── models/
├── notebooks/
├── reports/
├── screenshots/
├── dashboard/
├── README.md
├── requirements.txt
└── .gitignore

## Workflow

1. Load Dataset
2. Clean Data
3. Merge Sales, Calendar and Price Data
4. Feature Engineering
5. Exploratory Data Analysis
6. Train Random Forest Regressor
7. Evaluate Model
8. Save Model
9. Generate Predictions
10. Inventory Recommendations

## Machine Learning Model

Algorithm Used:

- Random Forest Regressor

Target Variable:

- Sales

Selected Features:

- Sell Price
- Month
- Day
- Week
- Quarter
- Day of Week
- Weekend Indicator
- Event Indicator
- SNAP Indicator

## Results

The Random Forest model successfully predicted retail sales trends.

Model outputs include:

- Actual vs Predicted Sales
- Feature Importance
- Inventory Recommendations
- Prediction CSV

## Inventory Recommendation

Based on predicted demand:

- Increase stock for products with high predicted demand.
- Maintain current stock for medium-demand products.
- Reduce inventory for products with low predicted demand.

These recommendations help minimize stockouts and reduce excess inventory.

## Future Improvements

- Implement time-series forecasting models such as Prophet or LightGBM.
- Build an interactive dashboard using Streamlit.
- Integrate real-time sales data.
- Deploy the model using a cloud platform.

## Author

**Revathi Chintha**

Data Analyst Aspirant

GitHub:
https://github.com/chintharevathireddy-blip