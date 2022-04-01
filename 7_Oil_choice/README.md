# Choosing a region for oil production

This **training** project is an example of building a regression model to predict the amount of oil reserves in 3 fields.

**Goal**: To determine, with 95% confidence interval, which well will produce the maximum (and positive) profit based on the predictions of the built model.

**Metric**:
RMSE
  
**Conditions of the problem**:
Only linear regression is suitable for training the model (the rest are not predictable enough).
During the exploration of the region, 500 points are explored, from which, using machine learning, the best 200 are selected for development.
The budget for the development of wells in the region is 10 billion rubles.
At current prices, one barrel of raw materials brings 450 rubles of income. The income from each unit of the product is 450 thousand rubles, since the volume is indicated in thousands of barrels.
After assessing the risks, you need to leave only those regions in which the probability of losses is less than 2.5%. Among them, choose the region with the highest average profit.
The data is synthetic.

### Description of data

id is the unique identifier of the well;
f0, f1, f2 - three signs of points (it doesn't matter what they mean, but the signs themselves are significant);
product is the volume of reserves in the well


## In the course of work, the following important points were made:

- Prepare data
- Build a model to predict the volume of reserves in new wells based on already known data
- Select wells with the highest value estimates
- Determine the region with the maximum total profit of selected wells
- Analyze possible profits and risks using the Bootstrap technique.
- Find average profit, 95% confidence interval and risk of loss

  
Each point must be accompanied by an explanation.





### Libraries used:

* pandas
* sklearn.linear_model.LinearRegression
* sklearn.metrics
* Bootstrap


*Project status*: finished

## Project conclusion: 

The model showed the highest profit in the third region. The RMSE of the third region is comparable to the RMSE of the first region. The region's RMSE 2 is small, but this may be due to the number of duplicates in the target column of the table. Also, the third region showed the smallest average negative profit of the lower threshold of the 95% confidence interval compared to the first. Based on the best profit, the lowest possible average loss and the inability to trust the RMSE value of the model for the 2nd region, I suggest choosing the third region for development.