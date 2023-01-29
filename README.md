# BIKE SHARING SYSTEM ANALYSIS USING A LINEAR REGRESSION MODEL

We want to understand the factors affecting the demand for shared bikes in the American market, based on various meteorological surveys and people's styles.
More specifically we want to know: 
1. Which variables are significant in predicting the demand for shared bikes.
2. How well those variables describe the bike demands 

We achieve this by building a Linear Regression model.

## Feature Selection
We use a hybrid combination of RFE and manual feature selection using P-values and VIF of predictors.

## Model Building
We build a linear regression model for predicting `cnt`, which is the count of total rental bikes including both casual and registered.

## Model Evaluation
We use R-squared score on the test set to evaluate our final model

## Assumptions
Standard assumptions for Linear Regression viz.
1. Linearity: The relationship between X and the mean of Y is linear.
2. Homoscedasticity: The variance of residual is the same for any value of X.
3. Independence: Observations are independent of each other.
4. Normality: For any fixed value of X, Y is normally distributed.

We shall visualize and validate our assumptions in this project.

## Business Goal
Our model will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Running the code
- The data is present in `day.csv`.
- To understand the data, please read `Data_Readme.txt`
- Download the repository, making sure that `day.csv` and `Bike Sharing Analysis.ipynb` are in the same folder.
- Now you can run the whole Notebook (`Bike Sharing Analysis.ipynb`) from top to bottom.
