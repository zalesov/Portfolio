# Predicting recovery of gold from ore

This project is an example of a task for the manufacturing industry.

Task: to build a model that should predict the recovery factor of gold from gold ore (2 parameters at once).
  
### Description of data
#### Technological process
* Rougher feed - feedstock
* Rougher additions (or reagent additions) - flotation reagents: Xanthate, Sulphate, Depressant
    * Xanthate ** - xanthate (promoter, or flotation activator);
    * Sulphate - sulfate (in this production, sodium sulfide);
    * Depressant - depressant (sodium silicate).
* Rougher process (English "rough process") - flotation
* Rougher tails - dump tails
* Float banks - flotation unit
* Cleaner process - cleaning
* Rougher Au - rough gold concentrate
* Final Au - final gold concentrate
Stage parameters
* air amount - air volume
* fluid levels - fluid level
* feed size - feed granule size
* feed rate - feed rate

#### Feature name


The name of the features should be:
[stage].[parameter_type].[parameter_name]
Example: rougher.input.feed_ag
Possible values for block [stage]:
* rougher - flotation
* primary_cleaner - primary cleaning
* secondary_cleaner - secondary cleaning
* final - final characteristics
Possible values for block [parameter_type]:
* input - raw material parameters
* output - product parameters
* state - parameters characterizing the current state of the stage
* calculation - calculated characteristics

The data is indexed by the date and time the information was received (the date attribute). Parameters adjacent in time are often similar.
Some parameters are not available because they are measured and/or calculated much later. Because of this, the test set lacks some features that may be in the training set. Also, there are no target features in the test set.
The initial dataset contains the training and test sets with all features.

### During the work there were the following important moments

- Complex, "dirty" production data
- Produced Exploratory data analysis
- The model must predict 2 parameters at once


### Libraries used:

* pandas
* numpy
* sklearn.metrics
* matplotlib.pyplot
* scipy.stats
* re
* sklearn.metrics
* sklearn.model_selection.cross_val_score
* sklearn.linear_model.LinearRegression
* sklearn.ensemble.RandomForestRegressor

*Project status*: finished

## Project conclusion: 

Initially, the calculations of the sMAPE metric were rechecked, the data was cleaned, prepared for analysis, further analyzed, anomalies were identified and discarded (about 10% of the data was lost), after that 2 models were trained and, as expected, the Random Forest model turned out to be the best. As a result, the task of predicting the sMAPE metric was completed with the value: sMAPE = 9.777336376209565
