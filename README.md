# Project Name
House Price Prediction
> Predict the significant variables for a housing company which can determine the price of houses. And How well those variables describe the price of a house?


## Table of Contents
* Steps followed for prediction task.
* Observations
* Conclusions
* Subjective Questions

<!-- You can include any other section that is pertinent to your problem -->

## Steps followed
- Reading and Understanding the data
- Data Cleaning
- Impute null values with meaningful data given in data definition.
- Drop column with high correlation based on correlation matrix.
- Data Encoding - creating dummies for categorical.
- Splitting the data into training and testing sets.
- Log transformation of target variable.
- Data Scaling : fitting scaler on train and transform on test
- Running Recursive Feature Elimination wto get 50 variables.
- Building linear regrssion model with 50 features.
- Ridge - Finding best params and alpha for ridge using GridSearchCV.
- Metric and Coefficient evaluation
- Lasso - Finding best params and alpha for ridge using GridSearchCV.
- Metric and Coefficient evaluation
- Model Evaluation and Comparison of Linear, Ridge and Lasso.
- Determining important features based on the magnitude of coefficients


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Observations
- 50 features taken from RFE
- Linear regression model was overfitting the data because dataset is too small.
- Ridge and Lasso removes the overfitting and perfoems better

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Conslusion
Important predictors for housing price were - GrLivArea,  OverallQual, OverallCond, GarageCars, TotalBsmtSF, BsmtFinSF1, LotArea

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
