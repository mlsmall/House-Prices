# House-Prices

This is regression problem that is part of Kaggle's machine learning competition. Information for this competition can be found [here](https://www.kaggle.com/c/house-prices-advanced-regression-techniques). The purpose of this competition is to predict the price of a house based on variables like size, neighborhood, house style, construction materials, and other characteritcs.

## Data Pre-Processing
 - Missing values in numerical variables were replaced with an interpolated value.
 - One-hot encoding was applied to categorical variables.
 
## Training Model Architecture
- Random forest regressor with 200 estimators that uses the mean squared error (MSE) as its criterion for measuring the quality of a split.
