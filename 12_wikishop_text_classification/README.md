# Determining if a tweet is toxic or not

This project is an example of an NLP problem.

**Task**: to create a binary classification model that, given the input text, will determine it as toxic or normal.

**Data Description**:

Corpus of tweets.

Each quantitative answer must be accompanied by an explanation.

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
* numpy
* torch
* transformers
* tqdm.notebook
* re
* sklearn.linear_model
* sklearn.model_selection
* nltk
* sklearn.ensemble.RandomForestClassifier
* GridSearchCV
* WordNetLemmatizer
* TfidfVectorizer
* matplotlib.pyplot
* nltk.corpus.wordnet

*Project status*: finished

## Project conclusion: 

The data has been loaded, cleaned, lemmatized and represented as vectors using tfidfVectorizer(). Hyperparameters were selected for the Random Forest Classifier, but despite this, the required F1-measure threshold was not reached. A logistic regression model was also trained, hyperparameters were selected and the required result was obtained.
