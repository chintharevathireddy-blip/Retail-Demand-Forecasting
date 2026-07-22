# Inventory Optimization Report

## Project Objective

The objective of this project is to forecast retail demand and provide inventory recommendations using historical sales data.

---

## Dataset

The project uses the M5 Forecasting Dataset, which contains:

- Historical daily sales
- Calendar information
- Product selling prices

---

## Inventory Recommendation Strategy

The trained Random Forest model predicts future sales.

Recommendations are generated based on the predicted demand.

### Rules

- Predicted Sales > Average Predicted Sales → Restock
- Predicted Sales ≤ Average Predicted Sales → Normal Stock

---

## Results

The inventory recommendation system classifies products into:

- Restock
- Normal Stock

These recommendations can help retailers:

- Reduce stock shortages
- Avoid overstocking
- Improve inventory planning

---

## Future Improvements

- Safety Stock Calculation
- Economic Order Quantity (EOQ)
- Dynamic Reorder Point
- Seasonal Inventory Planning