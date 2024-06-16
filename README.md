# Final Project for Econ 294A: Python Laboratory

## Project Overview
This project aims to identify the key determinants of housing prices in California using data from the 1990 Census. The analysis involves various regression techniques to compare their predictive performance. By examining the impact of variables such as location, median income, and proximity to the ocean, this study provides valuable insights for policymakers, investors, and urban planners, aiding informed decision-making and promoting sustainable development.

## Methodology
The dataset, sourced from Kaggle, consists of approximately 20,600 observations with variables such as longitude, latitude, median age of the house, total rooms, total bedrooms, population, households, median income, and ocean proximity. Using Python libraries like Numpy, Pandas, Statsmodels and sklearn; the data was cleaned, and a train-test split was performed. Various regression models were applied: OLS with fixed effects and interaction terms, Lasso, Ridge, Random Forests, and Quantile Regression. Model performance was assessed using the out-of-sample R-squared measure and k-fold cross-validation, highlighting the most influential factors and the predictive performance of different models.
