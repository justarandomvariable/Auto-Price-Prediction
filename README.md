# Automobile Price Prediction
**Domain:** Automotive | **Type:** Regression

## Overview
Predicting car prices using 26 features from the UCI Auto Imports dataset (205 cars, 1985).

## Key Findings
- Engine size and horsepower are the strongest predictors of price
- Price is right skewed — log transformation applied before modeling
- Random Forest outperformed all other models

## Models Compared
| Model | CV R2 |
|-------|-------|
| Random Forest | Best |
| Gradient Boosting | 2nd |
| Ridge Regression | 3rd |
| Linear Regression | 4th |
| Decision Tree | Overfit |

## Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## Files
- `auto_price_pred_final.ipynb` — main notebook
- `auto_imports.csv` — dataset
  
