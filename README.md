# Neural_Network_Charity_Analysis

## Overview of the analysis
In this project, I used machine learning to build a binary classifier that is capable of predicting whether applicants will be successful if they are funded by Alphabet Soup. I used a CSV with over 34,000 organizations that had been funded by Alphabet Soup. This dataset includes information about the organization's success, income, asking amount, and much more. 

## Results

### Data Preprocessing
- The Target Variable is IS_SUCCESSFUL
- The Feature Variables are APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS,  and ASK_AMT. 
- 'EIN' and 'NAME' were not relevant to our binary analysis as a target or a feature, so they were removed from the input data. 
- 
### Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why? </br>
I started out by using two hidden layers. The first layer had 80 and the second had 30. I used ReLu for my input layers and the Sigmoid activation for the output. 

- Were you able to achieve the target model performance? </br>
No. My model achieved 72.5% Acccuracy and the target model performance was 75%. 
</br> ![accuracy1](..images/accuracy1.png) 

What steps did you take to try and increase model performance?
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.

