# PCA of Housing Market Data

This repository contains the final project for "DTSA 5510: Unsupervised Algorithms in Machine Learning". The focus is on building predictive models for housing prices using two methods: Principal Component Analysis (PCA) and a supervised linear regression model with backward selection.

## Project Overview

In this project, we compare two approaches to predict housing prices:

- **PCA**: An unsupervised approach that reduces dimensionality and ensures no collinearity between features.
- **Backward Selection**: A supervised approach that filters out features based on correlation with the target variable and avoids multicollinearity.

### RMSE Comparison

The PCA model achieved a **7.4% lower RMSE** than the backward selection model, making it the better choice for pure prediction purposes. However, the backward selection model provided clearer insight into which features most affect housing prices.

## Key Features Impacting Housing Prices

From the supervised model, the following features had the most significant impact:
- **OverallQual**
- **YearBuilt**
- **1stFlrSF**
- **GrLivArea**
- **KitchenQual**
- **Fireplaces**
- **GarageCars**

## Conclusion

- **PCA** is recommended for prediction-focused tasks.
- **Backward Selection** is recommended for situations where interpretability is important.

## Sources

- De Cock, D. (2011). *Ames, Iowa: Alternative to the Boston Housing Data as an End of Semester Regression Project*. Journal of Statistics Education, 19(3).
- [Kaggle: House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)
- [Scikit-Learn: PCA](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html#sklearn.decomposition.PCA)
- [Towards Data Science: Principal Component Analysis](https://towardsdatascience.com/a-one-stop-shop-for-principal-component-analysis-5582fb7e0a9c)
