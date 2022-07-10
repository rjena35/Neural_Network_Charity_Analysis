# Neural_Network_Charity_Analysis

## Overview of the analysis: 
The purpose of this analysis is to use the features in the provided dataset to help create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.



## Results: 
### Data Preprocessing
* What variable(s) are considered the target(s) for your model?
  * "IS_SUCCESSFUL" column
  
![image](https://user-images.githubusercontent.com/98003050/178128403-c410fb73-c726-46ef-8b8c-ef21df596a32.png)

* What variable(s) are considered to be the features for your model?
 
 ![image](https://user-images.githubusercontent.com/98003050/178128424-67f2e163-c42e-4de8-ae53-e9eecb14bf91.png)


* What variable(s) are neither targets nor features, and should be removed from the input data?
  * The EIN was dropped from the input data


### Compiling, Training, and Evaluating the Model
* How many neurons, layers, and activation functions did you select for your neural network model, and why?
  * We used 3 hidden layers and 100 epochs. This increased the accuracy
* Were you able to achieve the target model performance?
  * It came very close with 74% accuracy
* What steps did you take to try and increase model performance?
  * Deciding to keep the "NAME" column improved the accuracy, along with adding another layer


## Summary: 
To sum it up, we were able to improve the accuracy to around 74%, not quite reaching our goal of <75.
