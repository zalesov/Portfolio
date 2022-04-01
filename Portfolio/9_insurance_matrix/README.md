# Algorithm for protection personal data of clients

This project is an example of a cryptography problem.

**Task**: create an algorithm that can change customer tabular data without loss of quality for model training

**Data Description**:

Archival data of clients of the insurance company

  
### In the course of work it is required:

- Come up with an algorithm for changing data without losing quality
- Justify the correctness of his work
- Check the correctness of the algorithm on the model
- R2 quality metric should not change
  
Each answer must be accompanied by an explanation.




### Libraries used:

* pandas
* numpy
* sklearn.metrics
* sklearn.linear_model.LinearRegression

  
*Project status*: finished

## Project conclusion: 

The value of the R2 metric on the modified sample, compared to the original one, changed slightly (4.5^(10^-11)) percent.
I consider the algorithm working, and the statement proven.
