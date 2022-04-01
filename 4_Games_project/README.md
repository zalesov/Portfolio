# Determining game sales success

This **learning** project is an analysis of sales data for games of various genres and platforms.

**Task**: It is required to identify patterns that determine the success of the game (by sales).

**Description of data**: Historical game sales data, user and expert ratings, genres and platforms (such as Xbox or PlayStation) are available from public sources.
Data up to and including 2016. Data for 2016 may not be complete.

### During the research it is required to answer the following questions:

- Explain why you filled in the gaps in a certain way or why you didn't;
  - Describe the reasons that could lead to omissions;
- Calculate total sales in all regions
- How many games were produced in different years? Is data for all periods important?
- How sales have changed by platform. Select the platforms with the highest total sales and plot the distribution by year. How long does it take for new platforms to appear and old ones to disappear?
- Take the data for the relevant current period. The main factor - these data will help build a forecast for 2017
- Which platforms are leading in sales, growing or falling?
- What can you say about the most profitable genres?
- Make a profile of the user of each region
- Test hypotheses
 - The average user ratings of the Xbox One and PC platforms are the same;
 - The average user ratings of the genres Action and Sports are different.

  
Each answer must be accompanied by an explanation.





### Libraries used:

* pandas
* matplotlib.pyplot
* scipy.stats
* plotly

*Project status*: finished

## Project conclusion: 

The data was pre-analyzed, the column names were changed, the data type was changed to more appropriate ones, the data was cleared of gaps, some missing values were removed,
some (in the ratings), due to the impossibility of replacing the subjective assessment and the value of "tbd" with the median, were replaced by zeros and were excluded from consideration in further analysis.

The total sales by region were calculated for each game, the games were analyzed by years, platforms, genres, the most appropriate time period was selected, the appropriate distributions were built, the most promising platforms were selected, a portrait of the buyer from the markets of different regions was compiled, the relationship between game sales and reviews was calculated users and critics, 2 hypotheses were also tested.


Important features of creating future advertising campaigns are proposed.