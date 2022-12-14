# Bike Sharing
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BikeIndia has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BikeIndia aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes. How well those variables describe the bike demands Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

Business Goal:
We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## General Information
- Reading and Understanding the Data
- Data Preparation
- Split the data
- Rescale data
- Build Model Manually
- Build Model with RFE
- Recommendations

## Reading and Understanding data
- Understanding Data in Categorical Columns
- Understanding Data in Numerical Columns
- Visualizing Numeric Variables
- Visualizing Categorical Variables
- Observations

## Data Preparation
- Drop the columns that are not needed for the Analysis
- For Categorical columns, pivot the categorical levels to features
- Check and update appropriate datatype

## Split the data
- Split the Data in to Training set and Testing set
- Training set should have 70% of the dataset and Testing should have 30% of the dataset

## Rescale data
- Use Standardization method and scale the training dataset

## Build Model Manually [ Model 1 ]
- Start with One variable Simple Linear Regression
- Add two more variables, one by one, [Forward] to make it a Multiple Linear Regression.
- Check the R2 of the linear regression summary.
- Add all the variables and remove one by one [Backward] to find our optimal model
- Remove features one by one such that the p-value for all the variables are less than 0.05 and VIF of all variables are less than 5.00
- Do the Residual analysis and check if there is a normalized curve on errors
- Use the model to Predict the target variable for the Test Data
- Evaluate the model
- Check the R2 score for the predicted Test data

## Build Model with RFE [ Model 2 ]
- Use Recursive Features Elimination [ RFE ] for Variables/ Features selection
- Create a model with those variable and check the p-values and VIF
- Remove features one by one such that the p-value for all the variables are less than 0.05 and VIF of all variables are less than 5.00
- Do the Residual analysis and check if there is a normalized curve on errors
- Use the model to Predict the target variable for the Test Data
- Evaluate the model
- Check the R2 score for the predicted Test data


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Check the R2 score and Adjusted R2 Score on both the models and decide on the model that can use to predict the Bike Rentals for the future data.


## Contact
Created by [@vprasath1902]
