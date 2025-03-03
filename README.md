# CodeAlpha-Project-Car-Price-Prediction

# Overview
This project is a Machine Learning-based system to predict the selling price of used cars. The dataset is sourced from Cardekho and contains information such as car name, manufacturing year, present price, kilometers driven, fuel type, seller type, transmission type, and ownership history.

# Dataset
The dataset consists of 301 records with the following columns:

- Car_Name: Name of the car
- Year: Year of manufacture
- Selling_Price: The price at which the car is being sold
- Present_Price: The current market price of the car
- Kms_Driven: The distance driven by the car (in km)
- Fuel_Type: Type of fuel (Petrol/Diesel/CNG)
- Seller_Type: Whether the seller is an individual or a dealer
- Transmission: Type of transmission (Manual/Automatic)
- Owner: Number of previous owners

# Data Preprocessing
- Converted Year to Age by subtracting it from 2025.
- Renamed certain columns for clarity.
- Handled categorical variables using one-hot encoding.
- Checked for missing values (none found).

# EDA
- Performed univariate analysis using count plots and box plots.
- Conducted bivariate/multivariate analysis using correlation heatmaps and pivot tables.
- Identified potential outliers in present price, selling price, and kilometers driven.

# Machine Learning Models Used
- Linear Regression
- Ridge Regression
- Lasso Regression
- Random Forest Regression
- Gradient Boosting Regression

# Model Evaluation
Each model was trained and evaluated using:
- R-squared (R2) score on training and test sets.
- Cross-validation (CV) score mean.
- Residual plots and scatter plots to assess performance.

# Best Performing Model
The Gradient Boosting Regressor achieved the highest performance with an R2 score of 0.94 on the test set, indicating strong predictive accuracy.

# Requirements
pip install pandas numpy matplotlib seaborn scikit-learn

# Future Improvements
- Include additional features like car brand, model, and location.
- Implement deep learning models for further improvement.

# Conclusion
This project successfully demonstrates the use of regression techniques to predict used car prices. The Gradient Boosting model performed the best, indicating its effectiveness in handling structured numerical and categorical data.



