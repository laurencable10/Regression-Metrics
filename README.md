# Regression Metrics
Lesson 3.04 | Regression Metrics
Introduction
We've learned a lot about linear regression models thus far.

How to fit linear regression models.
How to identify candidates for independent variables.
The assumptions of linear regression models and how to assess their validity.
One thing we haven't discussed in significant detail is how to measure the performance of a regression model.

What makes a good model?
What makes a bad model?
Between two good models, which should we pick and why?
Discussion: What makes a good model versus a bad model? How can we measure that?

Metrics, or measurements, will allow us to directly compare models that attempt to achieve the same goal.

Note: Depending on the metric, we might need to be wary of the scale of our YY values!
The Process of Data Science

Data Gathering
Data Cleaning/Munging
EDA
Modeling
Reporting
Model evaluation will mostly be used in steps 4 and 5.
Once we build models, we want to evaluate their performance!

# Regression Metrics 
## Using Forest Fires Data 
* This notebook builds upon linear regression knowledge with the Scikit-Learnn library - building upon fitting linaer regression models, identifying candidates for independent variables, and assessing validity through the assumptions of linear regression models - into detailing how to measure the performance of regression models * . 

* The dataset utilized contains burned area of forest fires in the northeast region of Portugal in addition to other attribute information including month, day, temperature, humidity, wind, etc. * 

## Overview 

### Building MLR Models to Predict Area Affected by Forest Fires
- Leveraging the Scikit-Learn library to build two different MLR models by : 
  - Define X and Y variables
  - Performing a train/test split
  - Fitting model on training data 
  - Making predictions on testing data 


### Regression Metrics 
- Characterizing and defining the goals for six different regression metrics
  - Mean Squared Error
  - Root Meann Squared Error
  - Mean Squared Log Error
  - Mean Squared Absolute Errot
  - $R^2$ Score  
  - Adjusted $R^2$ Score  
- Calculating regression metrics for the two MLR models built 

### Model Picking Based on Regression Metrics
- Comparing the regresssion metrics for the two MLR models built to determine the best performing model  
