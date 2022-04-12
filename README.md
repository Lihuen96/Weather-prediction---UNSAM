# Weather-prediction---UNSAM


practical work carried out for the subject Automatic Learning dictated by the project of interdisciplinary artificial intelligence of the Universidad Nacional de San Martín

## Objective

simulate the failure of a weather station and estimate the missing data using machine learning models

## Data

For this project, data was taken from 5 meteorological stations in the province of Cordoba, Argentina. The measurements, taken every 10 minutes, correspond to the period between January and December 2021.

## Conclusions

The metric used to measure the error was mean square error.
Initially, missing values were estimated using the mean. After training different machine learning models, the error decreased considerably.
The best model for temperature was the Support Vector Machine, for Humidity the XGBoost and for Precipitation the Linear Regression.
