# Time Series Data

you can run this code in jupyter notebook using visual studio code or anaconda.

In this task I analyse a time series data and visualize it.
the data contain **1259 rows × 2 columns** first column is the date and second column is the price which is the target for model to predicted.

I make the date as index then extract the time series data like (Price, day_of_week, quarter, month,	year,	day_of_year,	day_of_month,	week_of_year)
and I did the required preprocessing and split the data to 0.90% training and 0.10% testing to make it good for training the xgboost regressor model and make prediction.

after I train the xgboost model I see the feature importance and the result the most important feature are (year, day_of_year).
then I make the prediction on test set and get the following result **RMSE Score on Test set: 559.60**.

