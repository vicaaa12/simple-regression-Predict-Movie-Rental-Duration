Predict Movie rental duration using machine learning techniques.
Formatting time series features in applicable format and one-hot encoded categorical variables.
Started with simple linear regression model, than built decision tree model to capture non-linear relationship and finally used ensemble method bootstrap aggregating (bagging) Random Forest Regresser to predict continues variable. 
Used regularized tecniques Lasso to identify the most relevant features for Linear Regression - for future selection.
Evaluated the performance of each model using metrics like Mean Absolute Error (MAE) and R-squared (R2).
Used RandomSearch to find optimal hyperparameters for the best-performing model. 
Plot feature importance to understand which features contribute most to predicting rental duration. This helps in interpretability.
At the end created a simple pipeline that encapsulates the entire process. 
