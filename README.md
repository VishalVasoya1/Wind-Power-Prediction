# Wind-Power-Prediction
Machine Learning, Python, Data Visualization, Data Analysis

<h3>Title:</h3> 

Machine Learning for Wind Power Prediction and Analysis

<h3>Problem Statement:</h3> 

Wind power is a growing source of renewable energy, but its production can be variable and difficult to predict. Accurately predicting wind power production is important for managing energy grids and maximizing the use of wind power. This project aims to solve this problem by using machine learning to predict wind power production and performing additional analysis to gain insights into the factors that affect wind power production.

<h3>Solution:</h3>

We used Python along with the libraries numpy, pandas, matplotlib, and scikit-learn to analyze, visualize, preprocess, and model the wind power data. We started by importing the data into a pandas DataFrame and cleaning and preprocessing it. We then used matplotlib to visualize the data, including exploring the relationship between the wind speed and the power output.

For the modeling, we split the data into training and testing sets and applied two different models: linear regression and gradient boosted trees. We trained and evaluated each model using a variety of metrics, including mean squared error, mean absolute error, R-squared score, and explained variance score.

Our analysis included exploring the relationship between wind speed and power production by wind direction, month, and time of day. We found that wind power production was highest when wind speed was coming from the west and northwest directions. We also found that wind power production was highest in the winter months and during the hours of 8-10am and 5-7pm.

Our analysis of wind direction and wind speed can be useful for siting new wind turbines in locations where wind speed is highest. Our analysis of power production by month and time of day can be useful for managing energy grids and optimizing the use of wind power.

Our modeling results showed that the gradient boosted trees model performed better than linear regression, with lower mean squared error, mean absolute error, and higher R-squared score and explained variance score. This indicates that the gradient boosted trees model was better at predicting wind power production based on the wind speed data.

We also performed feature importance analysis to understand which variables were most important for predicting wind power production. We found that wind speed was the most important variable, followed by wind direction and temperature.

<h3>Metrics:</h3>

  <h3>Linear Model:</h3>

  R-squared score (R2 score): measures the proportion of variance in the dependent variable that is predictable from the independent variable(s). In this project,       the R2 score for the linear model was 0.88, indicating that the model explains 88% of the variance in the data.<br>
  Mean absolute error (MAE): measures the average absolute difference between the predicted and actual values. In this project, the MAE for the linear model was         353.<br>
  Root mean squared error (RMSE): measures the square root of the average squared difference between the predicted and actual values. In this project, the RMSE for       the linear model was 446.

  <h3>Gradient Boosted Trees Model:</h3>

  R-squared score (R2 score): measures the proportion of variance in the dependent variable that is predictable from the independent variable(s). In this project,       the R2 score for the gradient boosted trees model was 0.9813, indicating that the model explains 98.13% of the variance in the data.<br>
  Mean absolute error (MAE): measures the average absolute difference between the predicted and actual values. In this project, the MAE for the gradient boosted         trees model was 83.77.<br>
  Root mean squared error (RMSE): measures the square root of the average squared difference between the predicted and actual values. In this project, the RMSE for       the gradient boosted trees model was 179.
    
These metrics show that the gradient boosted trees model outperformed the linear model in terms of both R2 score and error metrics. The gradient boosted trees model was able to explain a higher proportion of the variance in the data and had lower errors (MAE and RMSE) compared to the linear model. However, it's important to keep in mind that the performance of the model may vary depending on the specific data and context it is applied to.

<h3>Conclusion:</h3>

In conclusion, this project demonstrates the use of machine learning for predicting wind power production and performing additional analysis to gain insights into the factors that affect wind power production. Our analysis of wind direction and wind speed, as well as power production by month and time of day, can be useful for siting new wind turbines and managing energy grids. We used Python along with popular libraries like pandas, numpy, and scikit-learn to analyze, preprocess, and model the wind power data. We found that gradient boosted trees performed better than linear regression for this task and wind speed was the most important variable for predicting wind power production. Our analysis and modeling results can be useful for improving the efficiency of wind power production and reducing our reliance on non-renewable energy sources.
