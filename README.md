Bike Rental Prediction
Overview :
This project aims to predict the expected count of bike rentals based on environmental, temporal, and seasonal features. By forecasting demand accurately, businesses can dynamically adjust rental prices, optimize fleet availability, and maximize revenue.

Objective:
Build a regression model to estimate the number of bikes rented per hour or day using historical data containing weather and seasonal information.

Dataset:
Dataset includes the following columns:
Date and Time-based: year, month, hour, weekday
Weather-related: temperature, humidity, windspeed
Categorical: season, holiday, workingday, weather
Target: count – total number of bikes rented

Approach:
Data Preprocessing:
Converted datetime into year, month, hour, and weekday features.
Scaled numerical features using MinMaxScaler.
Removed redundant columns and handled outliers.
Model Training
Implemented Linear Regression as the baseline model.
Used Polynomial Regression to capture non-linear relationships.
Evaluated using MAE, RMSE, and R² Score.

Outcome:
Polynomial Regression performed better than the baseline.
Model captures temperature, season, and time-based variations in demand.
Helps business predict rental count and optimize pricing dynamically.
Tools and Libraries
Python, Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn

