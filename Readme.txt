•	Project – Automobile Price prediction
Description: This data contains information of engine type, number of cylinders, fuel type, body style etc

Problem statement: We need to consider the above data and predict  automobile price.(Regression)

Challenges: These data have numerical and categorical data, so encoding must be used, it did not contain any null values, so imputation was not required.

Approach: First I understood the features and separated numerical and categorical data, applied one-hot encoding to categorical features, applied OLS model, where I got R^2 for test 0.89, again I thought this can be improved I have applied standard scalar and applied PCA, then I saw an improvement, I got a R^2 score of 0.91.

Tools used: Pandas, Python.

Results: PCA: 0.91
