# Regularization

This project aims to compare the performance of two popular regularization techniques: Lasso, Ridge. Regularaization is primarily used to combat overfitting. This project also use these techniques for feature selection, which means these techniques identify the features which affects the target variable the most. By evaluating and comparing the performance of these three methods, we aim to gain insights into their strengths and weaknesses in different scenarios.

## Lasso
Lasso regression is a powerful technique that not only performs regression but also serves as a feature selection method. It adds an L1 regularization term to the loss function, which encourages some feature coefficients to be exactly zero. This means that Lasso can effectively identify and select the most important features for your regression model.

## Ridge Regression
Ridge regression is another linear regression technique that adds an L2 regularization term to the loss function. It helps prevent overfitting by penalizing large coefficients.

## Principal Component Regression (PCR)
PCR combines principal component analysis (PCA) with linear regression. It reduces the dimensionality of the input features using PCA before performing linear regression.

## Dataset
The dataset for this project was pulled from the UCI's machine learning repository. This dataset examines the academic performance of secondary education students in two Portuguese schools. It encompasses a variety of data attributes such as student grades, demographic information, social factors, and school-related details. 

https://archive.ics.uci.edu/dataset/320/student+performance
