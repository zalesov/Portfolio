# Customer churn prediction

This **training** project is an example of building a binary classification model.

Purpose: to create a model that predicts whether a client will leave the bank or not.

**Data Description**:
Historical data on customer behavior and termination of agreements with the bank.

**Target feature**:
Exited - the fact that the client left

**metric**
F1-score

## Important nuances of the work

- Data preprocessing
- Class imbalance:
 - training the model without taking into account the imbalance
 - training the model taking into account the imbalance of classes


### Libraries used:

* pandas
* sklearn.model_selection
* sklearn.preprocessing
* sklearn.tree.DecisionTreeClassifier
* sklearn.metrics
* matplotlib.pyplot
* numpy
* sklearn.linear_model.LogisticRegression
* sklearn.ensemble.RandomForestClassifier
* sklearn.tree.DecisionTreeClassifier
* seaborn

*Project status*: finished

## Project conclusion: 

The data was cleaned, the task of classification was set; the data was split in a ratio of 3:1:1, a model was built and studied without taking into account the imbalance of classes; the imbalance was then studied and an appropriate class threshold was selected during the AUC-ROC analysis. Three models were analyzed: Logistic Regression, Decision Tree and Random Forest. The latter was chosen because it initially showed the best F1-measure value, the corresponding hyperparameters were selected, which showed the F1-measure value of 0.617 on the test set. and the AUC-ROC value: 0.741599.
