# House Price Prediction Report

## 1. Project Overview
This project predicts house prices using a Linear Regression model based on the LaunchML synthetic dataset.

## 2. Data Cleaning & Feature Engineering
- Missing numerical values were imputed using the column **median**.
- Missing categorical values were imputed using the column **mode**.
- Categorical features were converted into numerical features using **One-Hot Encoding**.

## 3. Model & Evaluation
- **Algorithm Used:** Linear Regression only.
- **Evaluation Metrics:** Evaluated using Root Mean Squared Error (RMSE) and R-squared ($R^2$).

## 4. Key Findings
- Property area and overall quality show a strong positive correlation with house prices.
- Linear Regression serves as a solid baseline for house price prediction tasks.
