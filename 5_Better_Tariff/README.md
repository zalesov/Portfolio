# Tariff recommendation

Task: to predict whether the client will switch to a new tariff line based on the characteristics of the object (archived data of the clients of a telecommunications company). Model quality metric: accuracy.

**Data Description**
Each object in the data set is information about the behavior of one user per month.
is_ultra — target attribute (1 - tariff "1" or 0 - another tariff, total tariffs 2)



### Libraries used:

* pandas
* scipy.stats
* seaborn
* matplotlib
* sklearn.tree.DecisionTreeClassifier
* sklearn.linear_model.LogisticRegression
* sklearn.metrics



*Project status*: finished

## Project conclusion: 

The data has been loaded and analysed. Then the data was divided into 3 samples in a ratio of 3:1:1 in two stages. 3 models were considered for classification, the model that showed the best result on the validation set was selected, after which various hyperparameters were tested for the best performance of the model. On the test sample, the final model showed an accuracy of 0.79.
There was also an attempt to test for adequacy, which the model, if such a test can be considered a test, successfully passed.