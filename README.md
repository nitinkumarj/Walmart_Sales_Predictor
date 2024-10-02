# Walmart_Sales_Predictor

## Description
This project aims to predict weekly sales for Walmart stores across various departments. By analyzing historical sales data, we can identify trends, seasonal patterns, and factor like holidays. The model developed uses machine learning techniques to forecast future sales, helping Walmart optimize inventory management, staffing, and promotions.

## Models

The following models were evaluated for bankruptcy prediction:
- Linear Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors
- XGBoost
- LightGBM

## Results

The table below shows the mean accuracy scores obtained during model training and validation.

| Model                 | Mean Accuracy (Train) | Mean Accuracy (Validation) |
|-----------------------|-----------------------|-----------------------------|
| Linear Regression               | 0.0901                 | 0.0912                       |
| Decision Tree         | 1.0                 | 0.9522                       |
| Random Forest         | 0.9968                 | 0.979                       |
| K-Nearest Neighbors      | 0.5266                 | 0.2828                       |
| XGBoost    | 0.9477                 | 0.939                       |
| LightGBM   | 0.914                 | 0.9091                       |



## Code Usage
1. Clone the repository.
2. Install the required dependencies (e.g., pandas, numpy, xgboost, lightgbm, matplotlib, seaborn).
3. Run the provided Python scripts in the appropriate environment.

## Future Work
- Explore additional feature engineering techniques.
- Experiment with different machine learning algorithms.
- Investigate ensemble methods for improved performance.
