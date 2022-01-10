# Prediction-with-Support-Vector-Regression
Here, we use a Support Vector Machine regressor (sklearn.svm.SVR), with various hyperparameters such as kernel="linear" (with various values for the C hyperparameter) or kernel="rbf" (with various values for the C and gamma hyperparameters) with the help of Grid Search. Then, we try replacing GridSearchCV with RandomizedSearchCV, and find that Randomized search tends to find better hyperparameters than grid search in the same amount of time. After, that we find the most important attributes and train the model with best parameters using only those features.
