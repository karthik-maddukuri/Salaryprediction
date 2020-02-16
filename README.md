# Salaryprediction
- Predicting Salaries | Python
The objective of this project was to create a model that predicts the salaries for the job postings based on features like job type, degree, major, number of years of experience, type of industry using Python.

- Imported and prepared the data using Pandas, explored the data using Seaborn and Matplotlib line plots, box plots, and heatmaps to look for correlations between salary and the dependent variables.
- Dropped the zero-valued observations in the salary column as jobs cannot have zero salaries.
- Correlation/heatmaps showed that the number of years of experience had a strong positive correlation and the number of miles from metropolis had a strong negative correlation with the target(salary) variable.
- Defined a function to obtain unique values from the categorical features(one_hot_encoder) to make better predictions.
- Decided the best model (GraidentBoostingRegressor) by obtaining the cross-validation scores using MSE as the metric(357.2) and predicted the salaries using the test data.
- I also created a dataframe of the feature importances. This revealed that Job type - Janitor was the most important feature
