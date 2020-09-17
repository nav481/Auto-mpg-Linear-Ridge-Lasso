# Auto-mpg Linear Regression and Regularization methods(Ridge and Lasso Regression)
Given data auto - mpg data set, different features (or explanatory variables), the aim is to predict the fuel consumption in MPG (miles per gallon).
Performed linear regression then for better accuracy perform Ridge and Lasso Regression.<br>
After data exploration and cleaning, preprocessed original features and used them to train a Linear Regression.
Generate the polynomial(degree -2) feature space then performed Ridge and Lasso Regression.<br>
The accuracy for linear regression is 81% for test set.<br>
After performing Ridge and Lasso the accuracy is 80% on training data, 84% on test data.<br>
To acheive better accuracy genrate polynomial(degree -2) feature space and this is the situation where the model is in over fitting.To get out of it, again use  Ridge and Lasso then accuracy is 89% on training data, 86% on test data for both Regularization methods.<br>
