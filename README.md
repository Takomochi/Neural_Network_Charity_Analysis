# Neural Network Charity Analysis

## Overview of the project
The project is to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup using machine learning and neural networks. 

## Resources
- Data: charity_data.csv
- Software: Google colaboratory

## Results
### Data Processing
- The columns `EIN` and `NAME` have been removed from the input data.
- Determine the number of unique values for each column, `APPLICATION_TYPE` and `CLASSIFICATION`. 
- Create Density plots
- Encode categorucal variables
- Split the dataframe into features and target.

### Compiling, Training, and Evaluating the Model

```
# First Attept
number_input_features = len(X_train_scaled[0])
nodes_hidden_layer1 = 80
nodes_hidden_layer2 = 30
```
```
# Second Attempt
number_input_features = len(X_train_scaled[0])
nodes_hidden_layer1 = 180
nodes_hidden_layer2 = 60
```
```
# Third Attempt
number_input_features = len(X_train_scaled[0])
nodes_hidden_layer1 = 160
nodes_hidden_layer2 = 60
nodes_hidden_layer3 = 30
```

## Summary
The deep learning model was not successful for reaching to the 75 % of accuracy. The highest accurary was 73 % with the 2nd Attempt model. Therefore, I would suggest to try other mochine learning models