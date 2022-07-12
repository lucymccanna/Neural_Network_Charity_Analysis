# Neural_Network_Charity_Analysis

## Overview of the Analysis
In Module 19, machine learning and neural netowrks are used to create a binary classifier capable of predicting whether applicants will be successful if funded by Alphabet soup. A CSV containing 34,000+ organizations that received funding from Alphabet Soup was analyzed based on their success.


## Results
#### **Data Preproprocessing**
* The IS_SUCCESSFUL column is considered the target for the model.
* Columns 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'INCOME_AMT', and 'SPECIAL_CONSIDERATIONS' are the variables that are considered the features for the model.
* Variables 'EIN' and 'NAME' are neither targets nor features and were removed from the unput data.

#### **Compiling, Training, and Evaluating the Model**
* Three hidden layers were selected for the final neural network (120, 60, 30 neurons). 
* Target model performance was not achieved. The maximum performance achieved was 72%.
* In attempt to increase model performance, an additional hidden layer was added. The neurons were also adjusted in attempt to increase performance.

## Summary
