# Predicting churn of clients

This **training** project is an example of the task of building a binary classification model

**Goal**: Build a model that predicts customer churn with a high ROC-AUC quality metric.

**Data Description**
The data consists of files obtained from different sources:
In all files, the customerID column contains the customer ID.
Information about contracts is current as of February 1, 2020.

- BeginDate - the date of the beginning of using the services,
- EndDate – end date of using the services,
- Type - payment type: monthly, annual, etc.,
- PaperlessBilling - cashless payment,
- PaymentMethod - payment method,
- MonthlyCharges - monthly spending on services,
- TotalCharges - total money spent on services
- Dependents - the presence of dependents
- Senior Citizen - the presence of retirement status by age
- Partner - the presence of a spouse (s)
- MultipleLines - the ability to maintain parallel lines during a call

**Quality metric:**
-ROC-AUC

### Features of this work:

- Lots of categorical variables
- Requires a high quality metric (roc_auc_score>0.88)
- Data is stored in different files
- Feature engineering
- Feature generation
- Selection of hyperparameters
- Class imbalance - Upsampling
  
Each step is required to be accompanied by an explanation.




### Libraries used:

* pandas
* numpy
* matplotlib.pyplot
* sklearn.metrics
* sklearn.model_selection
* sklearn.utils
* sklearn.linear_model.LogisticRegression
* sklearn.ensemble.RandomForestClassifier
* catboost.CatBoostClassifier
* RandomizedSearchCV
* GridSearchCV
* Upsampling

*Project status*: finished

## Project conclusion: 

The data was checked for gaps and duplicates, inappropriate rows (with the contract date of the current date February 1, 2020) were deleted, a new column "Customer Lifetime" was created, unnecessary columns for the model were dropped, a general pivot table was created, categorical variables were transferred to quantitative, different models were tested and the best one with the ROC_AUC value of 0.8929108701860313 was left on the test sample.
