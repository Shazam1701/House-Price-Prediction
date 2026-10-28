# House Price Prediction — ZMCM

## Overview
Machine learning project to predict residential property prices in the Mexico City Metropolitan Area (ZMCM) using property characteristics, demographic indicators, and accessibility metrics.

## Dataset
- **6,729 properties**
- **10 selected predictors**
- Target: `precio` (MXN)

## Methodology
- Data cleaning and exploratory data analysis (EDA)
- Feature selection and multicollinearity analysis
- Data leakage prevention
- 80/20 train-test split
- Linear Regression and Random Forest comparison
- Evaluation using MAE, RMSE, and R²

## Results

| Model | MAE (MXN) | RMSE (MXN) | R² |
|---|---:|---:|---:|
| Linear Regression | 2,711,639 | 4,306,847 | 0.7063 |
| Random Forest | 2,008,691 | 3,700,473 | 0.7832 |

Random Forest outperformed Linear Regression across all three metrics. Built area was the most influential feature, while predictions were less accurate for some high-priced properties.

## Tools
Python · Pandas · NumPy · Matplotlib · Seaborn · Scikit-learn

## Key Takeaway
An end-to-end regression workflow covering exploratory analysis, feature selection, model comparison, and interpretation of results.

## Graph Result

![Random forest Model's Graph Result]<img width="687" height="683" alt="image" src="https://github.com/user-attachments/assets/3d463429-52ba-4b2c-838b-af49a9661654" />


