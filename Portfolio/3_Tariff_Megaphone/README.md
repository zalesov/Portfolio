# Determination of a prospective tariff for a telecom company

This **learning** project is an example of a telecommunications company problem.

Description of the project:
The telecom company is developing 2 tariff plans.
Purpose: to find out which of the tariffs brings more revenue.
Description of data: history of using both tariffs by 500 users in 2018.

### During the research it is required to answer the following questions:

- Describe and analyze the behavior of the operator's customers based on the sample.
- Find how much each customer brings to the company
 - monthly revenue from each user (subtract the free limit from the total number of calls, messages and Internet traffic; multiply the remainder by the value from the tariff plan; add the subscription fee corresponding to the tariff plan).
- Test hypotheses:
 - the average revenue of users of the "Ultra" and "Smart" tariffs differ;
 - the average revenue of users from Moscow differs from the revenue of users from other regions.
 - Explain how you formulated the null and alternative hypotheses;
  what criterion was used to test the hypotheses and why.
- make a conclusion which tariff the company should choose


  
Each answer must be accompanied by an explanation.





### Libraries used:

* pandas
* matplotlib.pyplot
* numpy
* scipy.stats



*Project used*: finished

## Project conclusion: 

The data was analysed, cleaned, a general summary table was created, the requested calculations were made. Histograms of the corresponding distributions are constructed, user behavior is commented, and two hypotheses are tested.
  
The median revenue of users of the "Ultra" tariff is almost 2 times greater than the median revenue of users of the "Smart" tariff. Also, based on the histograms, it can be seen that despite the fact that users of the "Smart" tariff often do not fit into the free limit and pay for additional minutes / messages / traffic, unlike users of the "Ultra" tariff, which usually fit into the limit, the "Ultra" tariff still looks more preferable for the company, thanks to the high monthly fee, which is almost 4 times more than the "Smart" tariff
Based on this, we can conclude that the "Ultra" tariff is preferable for the company.
