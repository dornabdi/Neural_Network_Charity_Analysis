# Neural_Network_Charity_Analysis

## Overview of the analysis
In this project, I used machine learning to build a binary classifier that is capable of predicting whether applicants will be successful if they are funded by Alphabet Soup. I used a CSV with over 34,000 organizations that had been funded by Alphabet Soup. This dataset includes information about the organization's success, income, asking amount, and much more. 

## Results

### Data Preprocessing
- The Target Variable is IS_SUCCESSFUL
- The Feature Variables are APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS,  and ASK_AMT. 
- 'EIN' and 'NAME' were not relevant to our binary analysis as a target or a feature, so they were removed from the input data. 

### Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why? </br>
I started out by using two hidden layers. The first layer had 80 and the second had 30. I used ReLu for my input layers and the Sigmoid activation for the output. 

- Were you able to achieve the target model performance? </br>
No. My model achieved 72.6% Acccuracy and the target model performance was 75%. 
</br> ![accuracy1](..images/accuracy1.png) 

- What steps did you take to try and increase model performance?
- 1. I added another hidden layer with 15 additional neurons. Accuracy was 72.2%.
- 2. I added neurons to the second layer so that each layer has 80 neurons. Accuracy was 72.3%. 
- 3. I changed the activation function from ReLu to Tanh. Accuracy was 72.5%. 

## Summary/Recommendation: 
Despite my attempts to optimize the model, the best Accuracy level I got was 72.6% and a loss score of .56, which did not meet the designated threshold. The Accuracy means that "IS_SUCCESSFUL" was predicted correctly about 72.6% of the time. In other words, the model could predict organization sucess 72.6% of the time. Addiionally, I recommend using the Sigmoid activation function to take a better snapshot of the bigger picture and avoid overfitting by keeping data within a specific bounds. 

