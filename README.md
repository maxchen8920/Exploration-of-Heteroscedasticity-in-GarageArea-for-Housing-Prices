# Exploration-of-Heteroscedasticity-in-GarageArea-for-Housing-Prices

## Introduction
This Jupyter notebook aims to explore the effects of heteroscedasticity of independant variable 'GarageArea' on the robustness of regression models.
This exercise looks at the prediction of housing 'SalePrice' using only the single variable 'GarageArea'. The dataset is a modified version of the ["House Prices"](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) dataset from Kaggle.

## Findings
A Yeo-Johnson transformation was found to successfully eliminate heteroscedasticity within both variables and improve both linear and random forest regression models.
The linear regression model performed relatively better than the random forest model, suggesting that there may be a more linear relationship between the two variables.
The models both still performed quite poorly, showing that solely using 'GarageArea' to predict 'SalePrice' was not adequate.

## Files
`sale_price.ipynb` - an exploration of heteroscedasticity on sklearn regression models. Includes comments and plots. <br>
`datasets_houses.csv` - house prices dataset.
