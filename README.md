# new-york-cars-price-prediction
In this notebook there are the steps to make a regression model
- Data Cleaning
- EDA (using matplotlib, seaborn and plotly for visualization and scipy for some testing plus some feature extraction)
- Data Preprocessing (standardization, dimensionality reduction)
- Model Building (testing different models such as linear regression, neural networks and tree models) using sklearn, pytorch, tensorflow and statsmodels
- Fine tuning once the best performing model is selected we fine tune its parameters using grid search

The final model, obtained by using a gradient boosting, has a R2 coefficient of 91% and a RMSE 6654$ (much smaller than the average price for a car).
