# Deliverable 4

## Overview of Analysis
The purpose of this analysis was to create and optimize a machine learning model to classify the success rate of applications based on a variety of variables.

## Results
* Data Preprocessing
  * The variable that was considered the target was "IS_SUCCESSFUL" since it determined whether the application was successful or not, and met our needs to train/test our model.
  * All other variables except "EIN" and "NAME" were included as features, the reason why we droped EIN and NAME is because there was no perceived predictive values deriving from these columns.
* Compiling, Training, and Evaluation
  * I chose to have 3 hidden layers with 100, 30, and 10 neurons respectively. I chose to include this number of neurons and layers to increase the predictive/classifying power of my model. Since my initial model only had 2 hidden layers with 8 and 2 neurons respectively.
  * I was not able to acheive the target model performance - I was able to achieve a ~74% training score after optimization with an accuracy score of ~72%. 
  * To increase model performance I tried changing the binning for the application and classification features, while also dropping some features such as "SPECIAL_CONSIDERATIONS" and "AFFILIATIONS," changing my bucketing increased my overall accuracy while dropping features significantly decreased performance.
  
## Summary
I believe with more tweaking, my model could achieve the target model performance, however I believe that a random forest model would also be effective in this scenario. The reason is because it has similar capabilities in classifications while less resources intensive. 


 
