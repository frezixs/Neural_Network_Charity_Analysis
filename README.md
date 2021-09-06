# Neural_Network_Charity_Analysis

## Overview of the loan prediction risk analysis:

Create a Neural network to analyze the Charity dataset. 

## Results 

#### What variable(s) are considered the target(s) for your model?

IS_SUCCESFUL

#### What variable(s) are considered to be the features for your model?

STATUS, ASK_AMT, IS_SUCCESSFUL, APPLICATION_TYPE, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT

#### What variable(s) are neither targets nor features, and should be removed from the input data?

EIN NAME USE_CASE_Other AFFILIATION_Other

#### How many neurons, layers, and activation functions did you select for your neural network model, and why?
2-3 Hidden layers 
100 neurons for Layer 1 
50 neurons for Layer 2 
25 neurons for Layer 3 
Relu and Sigmoid since they are good for binary and non linear models 

#### Were you able to achieve the target model performance?
nearly 

#### What steps did you take to try and increase model performance?
Drop Noisy Features
![1630900157(1)](https://user-images.githubusercontent.com/49871539/132158131-0fa50c94-c3e0-4da5-ac64-c283c4c33bf1.png)

Adding hidden layers
![1630900181(1)](https://user-images.githubusercontent.com/49871539/132158161-c1511fe2-0799-49b3-be54-93941bb16a68.png)

Adding epochs 
![1630900208(1)](https://user-images.githubusercontent.com/49871539/132158196-1f7f45e0-68db-464c-b754-4bf4d9db7d9e.png)

Change activation functions
![1630900231(1)](https://user-images.githubusercontent.com/49871539/132158236-e924ff67-57eb-4702-82f3-3386ef6cd81d.png)



















