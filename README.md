# Neural_Network_Charity_Analysis
## Overview of Project
From Alphabet Soup’s business team, We received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. I use the features in the provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results
### Data Preprocessing
- What variable(s) are considered the target(s) for your model?

IS_SUCCESSFUL—Was the money used effectively

- What variable(s) are considered to be the features for your model?

APPLICATION_TYPE—Alphabet Soup application type

AFFILIATION—Affiliated sector of industry

CLASSIFICATION—Government organization classification

USE_CASE—Use case for funding

ORGANIZATION—Organization type

STATUS—Active status

INCOME_AMT—Income classification

SPECIAL_CONSIDERATIONS—Special consideration for application

ASK_AMT—Funding amount requested

- What variable(s) are neither targets nor features, and should be removed from the input data?

EIN and NAME

### Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?

Two hidden layers were used initially, 75 nodes were used in first hidden layer, 25 nodes were used in the second hidden layer.
Two different activation functions were used, "relu" activation function were used for the hidden layers and "sigmoid" activatio function was used for the output layer.

- Were you able to achieve the target model performance? 
 
Target accuracy of 75% is not achieved.

- What steps did you take to try and increase model performance?

Attempt 1: Additional hidden layer was added, Added more neurons for each hidden layer

Attempt 2: Removed fields that could be driving noise within the data, Changed the activiation function on the output layer, added one more bins with the "INCOME_AMT" coolumn for rare occurrences in columns

Attempt 3: Added the number of epochs to the training regime, Removed one more field that could be driving noise within the data

## Summary
None of the three attempts for optimization were able to achive the target accuracy of 75%, a different model is needed.
