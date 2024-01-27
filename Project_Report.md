# Table of Contents

1. Introduction
2. Exploratory Data Analysis
    2.1. Sale Price
    2.2. Numerical Features
    2.3. Categorical Features
    2.4. Correlations
    2.5. Missing Values
3. Data Preprocessing and Feature Engineering
    3.1. Missing Values
    3.2. Outliers
    3.3. Feature Engineering
        3.3.1. Create New variables
        3.3.2. Label Encoding
        3.3.3. Transform Numerical Variables to Categorical Variables
    3.4. Skewness and Normalizing Variables
    3.5. Feature Scaling
    3.6. One-hot Encoding
4. Modeling
    4.1. Regularized Regressions
    4.1.1. Ridge Regression
    4.1.2. Lasso Regression
    4.2. XGBoost
    4.3. LightGBM
    4.4. Averaging model
5. Conclusion
6. Reference


1. Introduction¶

The Ames Housing dataset was compiled by Dean De Cock for use in data science education. The data set describing the sale of individual residential property in Ames, Iowa from 2006 to 2010. The data set contains 2930 observations and a large number of explanatory variables (23 nominal, 23 ordinal, 14 discrete, and 20 continuous) involved in assessing home values.
First, I performed comprehensive exploratory data analysis to understand linear relationships among the most important variables and detect potential issues such as sknewness, outliers and missing values. Then, I handled these issues, cleansed the data and performed feature engineering. Lastly, I built machine learning models to predict house prices. By the time I write this notebook, my best model has Mean Absolute Error of ......................
