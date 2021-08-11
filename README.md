#  House Prices - Advanced Regression Techniques

Kaggle Competitions: [Link](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

## Competition Description

Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.


## data 

data: [Data](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)

*  Data descriptions
    
    *  Data descriptions
    
    * train.csv - the training set
    * test.csv - the test set
    * data_description.txt - full description of each column, originally prepared by Dean De Cock but lightly edited to match the column names used here

    * sample_submission.csv - a benchmark submission from a linear regression on year and month of sale, lot square footage, and number of bedrooms


## Goal
 
 predict the sales price for each house. For each `Id` in the test set,  must predict the value of the **SalePrice** variable. 

##  Metric

Submissions are evaluated on **Root-Mean-Squared-Error (RMSE)** between the logarithm of the predicted value and the logarithm of the observed sales price



