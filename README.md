## Problem Statement

Analyze the Ames Iowa housing data and apply machine learning concept to build a model that can predict the sale price of the houses.
    
    
## Executive Summary

Buying a home can be tricky since you cannot measure every aspect of the house and predict the right sale price of the house. So, a model that takes in the measures in order to predict the house price can be useful to the people when buying a house. Therefore, we obtain the housing dataset which include 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa. We will use this dataset to see which house features have negative or positive effect of the house price and build a accurate model that can predict the sale price.  


## Data Dictionary

The data are given:
- train.csv
- test.csv

- Check __[This link for data dictionary](http://https://www.kaggle.com/c/dsi-us-6-project-2-regression-challenge/data)__

## Method

- Import and check the data
- Identify data types and missing values
- Handle missing values and clean the data
- Create charts and graphs to identify trends
- Analyze the relationship between sale price and predictors
- Evaluate the predictors and build a model
- Check the performance of the model
- Interpret the model 


## Conclusion/Recommendation

**Model**
- Elastic Net method
- Train Score = 0.909
- Test Score = 0.902
- Error(RMSE) = $35467.47

**Features that help the sale price to increase**
- High positive coefficient:
    - Gr Liv Area: above ground living area in square feet
    - Total Area: area of basement, 1st floor and 2nd floor in square feet
    - Neighborhood Crawfor: Crawford neighborhood in Ames, Iowa (Expensive neighborhood?)
    - Exterior 1st_BrkFace: Brick Face exterior covering on house

**Features that help the sale price to decrease**
- High negative coefficient
    - Roof Matl_ClyTile: Clay or tile roof material
    - Functional_Sal: Home functionality rating (salvage only)
    - Functional_Sev: Home functionality rating (severely damaged)
    - Neighborhood_Edwards: Edwards neighborhood in Ames, Iowa (Inexpensive neighborhood?)
