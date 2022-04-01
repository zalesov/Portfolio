# Determining the cost of cars

This project is an example of building a regression model.

**Task**: to build a model that can predict the car's price in the market based on the parameters of the car. For the "customer", in addition to quality, the time of work and training of the model is important.

It is required to do data preprocessing feature engineering.

## Description of data

### Features
* DateCrawled - date of downloading the profile from the database
* VehicleType - type of car body
* RegistrationYear - year of registration of the car
* Gearbox - type of gearbox
* Power - power (hp)
* Model - car model
* Kilometer - mileage (km)
* RegistrationMonth - month of car registration
* FuelType - type of fuel
* Brand - car brand
* NotRepaired - was the car under repair or not
* DateCreated - date of creation of the profile
* NumberOfPictures - the number of photos of the car
* PostalCode - postal code of the owner of the profile (user)
* LastSeen - date of last user activity
### Target feature
* Price - price (EUR)


**Quality Metric**:
  
RMSE


### In this work, the following points were important:

- data preparation
- prediction quality
- prediction speed
- studying time
- use LightGBM

  
Each stage of the work is required to be accompanied by an explanation.


### Libraries used:

* pandas
* numpy
* matplotlib.pyplot
* sklearn.metrics
* sklearn.ensemble.RandomForestRegressor
* sklearn.linear_model.LinearRegression
* LightGBM

*Project status*: finished

## Project conclusion: 

The data was loaded, cleaned, prepared for further training through OHE, divided into training, validation, test sets, 3 models were considered, the best hyperparameters for Random Forest and LightGBM models were selected, the result and time of training and prediction were analyzed and a conclusion was made.
