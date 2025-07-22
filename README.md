Flight Price Prediction using Regression Models :
This project aims to predict flight prices using a machine learning approach. The dataset includes both labels (e.g., airline, source, destination) and the target variable Price. We apply three regression algorithms and select the best-performing model for final predictions.

Dataset Overview:

Features: Airline, Source, Destination, Duration, Total Stops, Departure Date, etc. Target: Price of the flight Format: CSV

Preprocessing the Data:

Before prediction, the data needs to be cleaned and transformed:

Convert dates and times into features like day, month, hour
Calculate duration in minutes or hours to make it numerical
Convert categories like airline names or cities into usable numbers
Remove missing or incorrect values
Optionally scale the numbers so they’re on similar ranges
Regression models used:

1.Linear regression 2.Decision tree regressor 3.Random forest regressor 4.XGBoost regressor

Model Evaluation:

Models were evaluated using:

Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
R² Score The model with the best performance (lowest RMSE & highest R²) was selected for final prediction.
Final Predictions:

Once the best model is chosen (often XGBoost), it's retrained with all the available data to improve accuracy. Then it can be used to predict prices for future or unknown flights.
