# Medical-Insurance-Cost-Prediction
## Overview
Predicting and explaining individual medical insurance costs using demographic and lifestyle data, with an emphasis on interpretability and principled model selection.
## Dataset
Medical Insurance Cost dataset (Kaggle): https://www.kaggle.com/datasets/hetmengar/medical-insurance-cost-prediction/data
~1,300 observations, no missing values after cleaning.
Target: charges
Features: age, sex, BMI, children, smoking status, region
## Modeling
Models evaluated:
Linear Regression
Ridge & Lasso
Random Forest
Final model: Linear Regression on log-transformed charges
R² ≈ 0.87, outperforming Random Forest after domain-informed feature engineering
## Technologies
Python, pandas, NumPy, scikit-learn, matplotlib, seaborn
## Conclusion
This project demonstrates that thoughtful EDA and domain-driven feature engineering can allow simple, interpretable models to outperform more complex alternatives on structured healthcare data.
