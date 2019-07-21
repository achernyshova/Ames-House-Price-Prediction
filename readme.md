# Project 2. House Price Prediction


## Problem Statement
> - The goal for this project use linear regression techniques in order to estimate the sales price of houses in Ames, Iowa.

## Dataset
 > - Dataset from Kaggle Competition
 > - Dataset contains house sale prices and its features for houses
sold in Ames between January 2006 and July 2010
 > - 2930 observations in dataset
 > - 81 attributes - nominal, ordinal, discrete, and continuous

Data dictionary is here:  http://jse.amstat.org/v19n3/decock/DataDocumentation.txt

## Repo Structure
> - Code folder - Contains all Jupyter notebooks:

      1. 01_Train_Cleaning_and_EDA.ipynb
      2. 02_Kaggle_Cleaning.ipynb
      3. 03_Preprocessing_Feature_Engineering_and_Modeling.ipynb

> - Datasets folder - Contains .csv files  - original training and test data sets, cleaned data sets for both test and training data sets, submission to Kaggle competition.





## Executive Summary
The project will do the following parts:
1. Cleaning the Train and Test datasets
2. Doing an EDA
3. Features engineering
4. Building and fitting the model
5. Evaluating the model


## Conclusions and findings
The model with the highest r2 score is LASSO regression model with 80 features. The RMSE for this model was $20,912.
The most likely predictors of house price are square footage of a house and overall quality.


## Next steps
Learn and use other types of models and techniques to improve the metrics of predictions
