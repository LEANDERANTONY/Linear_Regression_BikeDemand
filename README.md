# Linear_Regression model for Bike Demand

> The project aims to find the driver variables that significantly affect the demand for rental bikes in the yaers 2018 and 2019 in the US.

## Table of Contents

- General Information
- Conclusions
- Software Used
  

<!-- You can include any other section that is pertinent to your problem -->

## General_Information:

- A multiple linear regression model is developed to predict the demand for bike rentals for the bike sharing company 'BOOMBIKES'.
- The data is split 70:30 to train and test sets respectively.
- Various models are developed and tools like RFE is used to reduce issues of 'Multicollinearity' and a statistically significant model is selected.
- Residual analysis is done to ensure the model conforms to the assumptions of linear regression like 'Homoscedasticity'.
- The model is then used to predict on the test set and evaluations are done as per standard practices.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions:

- The features temperature and weather are the strongest predictors of demand for bikes in the years 2018 and 2019.
- The demand for bikes has also improved across the two years.
- The feature variables are able to account for 82% variation in the target variable with an adjusted R2 score of **0.82**.
- The final model has a low Prob(F-Statistic) value of 1.25e-181, suggesting it is statistically significant.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
## Software

- Jupyter - version 3.9.13
- Visual studio code - version 1.83.0
- git - version 2.42.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->
## Contact
Created by LeanderAntony - feel free to contact me on antony.leander@gmail.com


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
