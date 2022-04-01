**This repository contains my completed studying projects of Yandex.Practicum**

## 1. Bank scoring
https://github.com/zalesov/Portfolio/tree/main/1_bank_scoring

It is required to analyze the factors that increase the probability of loan default.

### Technologies used:

*pandas
*pymystem3

## 2. Real estate market analysis in St. Petersburg
https://github.com/zalesov/Portfolio/tree/main/2_Flats_in_SP

Using real estate sales data, analyze the real estate market in St. Petersburg

### Technologies used:

*pandas
*matplotlib
*numpy

## 3. Choosing the optimal tariff plan
https://github.com/zalesov/Portfolio/tree/main/3_Tariff_Megaphone

Using data on the use of communication services, choose the most profitable tariff for the telecommunications company

### Technologies used:
*pandas
* matplotlib
*numpy

## 4. Game sales analysis
https://github.com/zalesov/Portfolio/tree/main/4_Games_project

It is required to identify patterns that determine the success of the game (for sales)

### Technologies used:

*pandas
* matplotlib.pyplot
* scipy.stats
* plotly


## 5. Tariff recommendation
https://github.com/zalesov/Portfolio/tree/main/5_Better_Tariff

It is necessary to predict whether the client will switch to a new tariff line based on the characteristics of the object (archival data of the telecommunications company's clients). Model quality metric: accuracy.

### Technologies used:

*pandas
* scipy.stats
* seaborn
* matplotlib
* sklearn.tree.DecisionTreeClassifier
*sklearn.linear_model.LogisticRegression
*sklearn.metrics



## 6. The outflow of customers from the bank
https://github.com/zalesov/Portfolio/tree/main/6_Bank_leavers

The purpose of the work is to create a model that predicts whether the client will leave the bank or not. Quality metric: f1-measure

### Technologies used:

*pandas
*sklearn.model_selection
*sklearn.preprocessing
* sklearn.tree.DecisionTreeClassifier
*sklearn.metrics
* matplotlib.pyplot
*numpy
*sklearn.linear_model.LogisticRegression
*sklearn.ensemble.RandomForestClassifier
* sklearn.tree.DecisionTreeClassifier
* seaborn

## 7. Choosing a location for the well
https://github.com/zalesov/Portfolio/tree/main/7_Oil_choice

Linear regression to predict and Bootstrap technique to confirm with 95% confidence interval break-even location for oil production.

### Technologies used:

*pandas
* from sklearn.linear_model import LinearRegression
*sklearn.model_selection
*sklearn.metrics
* Bootstrap

## 8. Predicting Remaining Gold After Refining
https://github.com/zalesov/Portfolio/tree/main/8_Cyfra_project

It is required to build a model that should predict the recovery factor of gold from gold ore (2 parameters at once).


### Technologies used:

*pandas
*numpy
*sklearn.metrics
* matplotlib.pyplot
* scipy.stats
*re
*sklearn.metrics
* sklearn.model_selection.cross_val_score
*sklearn.linear_model.LinearRegression
* sklearn.ensemble.RandomForestRegressor

## 9. Encryption matrix
https://github.com/zalesov/Portfolio/tree/main/9_insurance_matrix

Task: to create an algorithm that can change the tabular data of customers without loss of quality for model training.

### Technologies used:

*pandas
*numpy
*sklearn.metrics
*sklearn.linear_model.LinearRegression

## 10. Car price prediction
https://github.com/zalesov/Portfolio/tree/main/10_Cars_pricing

It is necessary to build a model that can predict the car's price on the market based on the parameters of the car. For the "customer", in addition to quality, the time of work and training of the model is important

### Technologies used:

*pandas
*numpy
* matplotlib.pyplot
*sklearn.metrics
* sklearn.ensemble.RandomForestRegressor
*sklearn.linear_model.LinearRegression
* LightGBM


## 11. Predicting the number of taxi orders
https://github.com/zalesov/Portfolio/tree/main/11_taxi_time_series

The goal is to predict the number of taxi orders for the next hour

### Technologies used:

*pandas
*statsmodels.tsa.seasonal
* matplotlib.pyplot
*sklearn.linear_model.LinearRegression
* sklearn.ensemble.RandomForestRegressor



## 12. Tweet classification
https://github.com/zalesov/Portfolio/tree/main/12_wikishop_text_classification

It is required to create a binary classification model that, based on the input text, will determine it as toxic or normal.

### Technologies used:

*pandas
*numpy
*torch
* transformers
* tqdm.notebook
*re
* sklearn.linear_model
*sklearn.model_selection
*nltk
*sklearn.ensemble.RandomForestClassifier
* GridSearchCV
* Word Net Lemmatizer
* TfidfVectorizer
* matplotlib.pyplot
*nltk.corpus.wordnet

## 13. Computer vision
https://github.com/zalesov/Portfolio/tree/main/13_Computer_vision

It is necessary to build a neural network that will determine the age of a person from a photograph (The photograph is served as a matrix with information about each pixel)

### Technologies used:

*pandas
*numpy
*tqdm
* tensorflow.keras
* tensorflow.keras.models.Sequential
*tensorflow.keras.applications.resnet.ResNet50
*tensorflow.keras.optimizers.Adam
* tensorflow.keras.preprocessing.image.ImageDataGenerator
* tensorflow.keras.layers
 *Conv2D
 * Flattens
 * Dense
 *AveragePooling2D
 *AvgPool2D
 *GlobalAveragePooling2D



## 14. Binary classification
https://github.com/zalesov/Portfolio/tree/main/14_Final_project

It is required to build a binary classification model that will predict the outflow of customers with a high ROC-AUC quality metric.

### Technologies used:

*pandas
*numpy
* matplotlib.pyplot
*sklearn.metrics
*sklearn.model_selection
*sklearn.utils
*sklearn.linear_model.LogisticRegression
*sklearn.ensemble.RandomForestClassifier
* catboost.CatBoostClassifier
*RandomizedSearchCV
* GridSearchCV
* Upsampling