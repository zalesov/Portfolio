# Apartment sales advertising research

The purpose of this **educational** project is to determine the parameters that affect the market value of real estate.

Data - archive of ads for the sale of apartments in St. Petersburg and neighboring settlements for several years from the real estate sale service.
  
There are two types of data available for each property offered for sale. The first ones are entered by the user, the second ones are obtained automatically on the basis of cartographic data. For example, the distance to the center, airport, nearest park, etc. 
  
Требуется произвести data preprocessing feature engineering.

### During the research it is required to answer the following questions:

- Describe how long a sale usually takes. When can sales be considered very fast, and when unusually long?
- What factors most influence the cost of an apartment? Learn if the price depends on a square meter, number of rooms, floor (first or last), distance from the center?
- Is there a dependence on the date of placement: day of the week, month and year?
- Find the 10 locations with the most ads. Calculate the average price per square meter in these settlements. Highlight the settlements with the highest and lowest cost of housing
- Find out which region is included in the "center" of St. Petersburg? (answer must be given in kilometers and calculate the average price for each kilometer)
- Analyze the features of real estate in the city center
- Do the results for the whole region differ from those for the center, and if so, how?

  
Each answer must be accompanied by an explanation.





### Libraries used:

* pandas
* matplotlib  
* numpy

*Project used*: finished

## Project conclusion: 

The data was analyzed, cleaned, the data type of some columns was changed, patterns were identified in the factors affecting the price of real estate, the radius of apartments in the center, the segment itself were also identified, patterns were identified.
The behavior of real estate sellers in the center of St. Petersburg does not differ from the behavior of real estate sellers in St. Petersburg as a whole. Differs in price and area: median area in St. Petersburg = 56.0, and prices = 5650000.0, and in the center: median price: 9900000.0, and median area: 86.0.
