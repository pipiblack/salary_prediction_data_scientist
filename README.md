# salary_prediction_data_scientist
I built a model to predict salaries for data scientists, based on several factors as : experience, company, state of residence and  type of job.
Perfomed EDA on the set, as the data was previously cleaned so went directly to exploratory data analysis
Built  a linear regression model on the data
Lasso regression on the training data
Built a RangomForest regressor model on the data
performed gridsearchCV to  select the best model

Esed cros_val_score,MAE,MSE metrics to test the accuracy of the model

From this The RandomForestRegressor seemed to outdo the the other models and is therefore a good fit for the data
