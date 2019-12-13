# dsi-project2
## DSI Project 2- Ames Housing Prediction
#### Use the well known Ames housing data to create a regression model that predicts the price of houses in Ames, IA.

## Data Dictionary
#### A copy of the dictionary can be found here : 
https://www.kaggle.com/c/dsi-us-6-project-2-regression-challenge/data

#### Definition of the new column added:

|Feature|Type|Description|
|---|---|---|
|total_score|int|total quality score of the house

Formulae for total_score:  ('Overall Qual' * 'Exter Qual' * 'Kitchen Qual' * 'Bsmt Qual')

## Executive Summary
Based on the dataset given, the followin steps were carried out:
1. Data Import
2. Data Cleaning & Pre-processing
3. Exploratory Data Analysis
4. Create Model (LinearRegression, Lasso Regularization, Ridge Regularization)
5. Evaluate Model
6. Make Predictions for Test Data

## Conclusions
In this project, the dataset given was checked, cleaned and pre-processed before model creation and evaluation. Filter Method chosen to pre-select the top correlated features with our target variable 'SalePrice' proved to be beneficial as this cut down the amount of time needed to go through all 79 variables. With that, I have more time to work on feature creation and to improve model accuracy.

During the feature creation process, I have tried to create several interaction terms but only total_score shown to be effective in helping the model to perform better. I have learnt that a good understanding of the underlying dataaset is crucical in determing how and what new features can be created to help the model to improve its accuracy.

It was observed that Lasso/Ridge regularization methods were able to handle multi-collinearity automatically. This was extremely useful for projects with large no. of variables.
