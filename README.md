# Neural_Network_Charity_Analysis

## Purpose
The purpose of this analysis is to create a neural network model that is capable of predicting with 75% accuracy whether applicants will be successful if funded by Alphabet Soup

## Results

### Data Preprocessing
- The IS_SUCCESSFUL variable is the target for this model
- The APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT are features of this model
- The EIN and NAME variables are neither targets or features and were removed from this model

### Compiling, Training, and Evaluating the Model
- In the last attempt at getting the model over 75% accuracy the model had 331 neurons, 3 hidden layers, and both the sigmoid and relu activation functions built in. The large number of and 3 hidden layers were an attempt to increase accuracy at risk of overfitting.
- In the tests that were performed I was not able to achieve target model performance of 75%.
- I increased the number of neurons, added an additional hidden layer, increased the number of epochs, and experimented with different activation functions to try to increase the model’s performance.
## Summary  
The final version of the model achieved an accuracy score of .73% and a loss score of .58
