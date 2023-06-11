# Predict_orderamount_for_B2BCompanies
# Problem Statement for ML Model 
To build a Machine Learning Model to predict the order amount, customers might make in the upcoming days.
# Order Dataset:
https://drive.google.com/file/d/1fibNQLLqn33xD3NcIv7Ck7eGppBS1l8v/view?usp=sharing

# Work Description
In this work, a regression model was developed to predict the "amount_in_usd" based on various features from the dataset. The dataset was preprocessed by handling missing values, encoding categorical variables, and transforming skewed features using log transformation. The data was then split into training and testing sets.

Initially, a linear regression model was trained on the selected numeric features, and its performance was evaluated using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R-squared (R^2). The model achieved good performance, with low values for MSE, RMSE, and MAE, indicating accurate predictions and a high R^2 score, indicating a good fit to the data.

Furthermore, additional models such as Support Vector Machine (SVM), Random Forest, and AdaBoost were implemented and evaluated using cross-validation and hyperparameter tuning. These models were trained and tested using the selected numeric features and performed well in terms of accuracy and predictive capability.

PCA (Principal Component Analysis) was also performed to reduce the dimensionality of the dataset and identify the most influential features. The feature influence scores were plotted to visualize the importance of each feature in achieving dimension reduction.

Overall, this work demonstrates the development and evaluation of regression models for predicting the "amount_in_usd" variable. The models showed good performance, accurately capturing the relationships between the selected features and the target variable. The findings provide insights into the dataset and can be utilized for predicting the amount of credit released in the future based on the given features.
