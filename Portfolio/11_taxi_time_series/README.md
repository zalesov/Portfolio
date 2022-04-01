# Predicting taxi orders

This project is an example of a time series prediction problem.

**Target**:
predict the number of taxi orders for the next hour

**Data Description**:
Historical data on taxi orders at airports.

**Model Quality Metric**:
RMSE




### During the research, the following questions are required to be answered:

- resampling by one hour
- Data analysis
- Building a model with an RMSE indicator on a test sample of no more than 48
  
Each step is required to be accompanied by an explanation.





### Libraries used:

* pandas
* statsmodels.tsa.seasonal
* matplotlib.pyplot
* sklearn.linear_model.LinearRegression
* sklearn.ensemble.RandomForestRegressor



*Project status*: finished

## Project conclusion: 

The data was loaded, resampled, then the data was analyzed, additional features were prepared, and the final model with fitted hyperparameters showed an RMSE value of less than 48.
