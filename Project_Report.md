# Table of Contents

1. Introduction
2. Exploratory Data Analysis<br>
    2.1. Sale Price<br>
    2.2. Numerical Features<br>
    2.3. Categorical Features<br>
    2.4. Correlations<br>
    2.5. Missing Values<br>
3. Data Preprocessing and Feature Engineering<br>
    3.1. Missing Values<br>
    3.2. Outliers<br>
    3.3. Feature Engineering<br>
        3.3.1. Create New variables<br>
        3.3.2. Label Encoding<br>
        3.3.3. Transform Numerical Variables to Categorical Variables<br>
    3.4. Skewness and Normalizing Variables<br>
    3.5. Feature Scaling<br>
    3.6. One-hot Encoding<br>
4. Modeling<br>
    4.1. Regularized Regressions<br>
    4.1.1. Ridge Regression<br>
    4.1.2. Lasso Regression<br>
    4.2. XGBoost<br>
    4.3. LightGBM<br>
    4.4. Averaging model<br>
5. Conclusion<br>
6. Reference<br>


1. Introduction¶

The Ames Housing dataset was compiled by Dean De Cock for use in data science education. The data set describing the sale of individual residential property in Ames, Iowa from 2006 to 2010. The data set contains 2930 observations and a large number of explanatory variables (23 nominal, 23 ordinal, 14 discrete, and 20 continuous) involved in assessing home values.
First, I performed comprehensive exploratory data analysis to understand linear relationships among the most important variables and detect potential issues such as sknewness, outliers and missing values. Then, I handled these issues, cleansed the data and performed feature engineering. Lastly, I built machine learning models to predict house prices. By the time I write this notebook, my best model has Mean Absolute Error of ......................
