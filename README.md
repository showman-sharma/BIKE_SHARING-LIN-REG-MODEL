# BIKE SHARING SYSTEM ANALYSIS USING A LINEAR REGRESSION MODEL

## Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. 
We want to understand the factors affecting the demand for shared bikes in the American market, based on various meteorological surveys and people's styles. More,  specifically we want to know: 
1. Which variables are significant in predicting the demand for shared bikes.
2. How well those variables describe the bike demands 


## Business Goal
Our model will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Feature Selection
We use a hybrid combination of RFE and manual feature selection using P-values and VIF of predictors in a model.

## Model Building
We build a linear regression model for predicting 'cnt', which is the count of total rental bikes including both casual and registered.

## Model Evaluation
We you use the following two lines of code to calculate the R-squared score on the test set.

```python
from sklearn.metrics import r2_score
r2_score(y_test, y_pred)
```

## Assumptions
Standard assumptions for Linear Regression viz.
1. Linearity: The relationship between X and the mean of Y is linear.
2. Homoscedasticity: The variance of residual is the same for any value of X.
3. Independence: Observations are independent of each other.
4. Normality: For any fixed value of X, Y is normally distributed.

We shall even visualize how acceptable our assumptions are in this project.
