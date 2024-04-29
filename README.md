# Ride Sharing Demand Competition - Kaggle

## Overview
This repository contains the code and resources for participating in the Ride Sharing Demand Competition on Kaggle. The competition involves predicting the demand for ride-sharing services based on various features such as time, weather conditions, and other relevant factors.

## Data
The dataset provided for the competition includes historical ride-sharing data with features such as:
- Datetime
- Season
- Holiday
- Workingday
- Weather
- Temperature
- Feeling Temperature
- Humidity
- Windspeed

Additionally, the dataset contains the target variable 'count', representing the number of ride-sharing bookings at a given time.

## File Descriptions
- `train.csv`: Training dataset containing historical ride-sharing data.
- `test.csv`: Test dataset for making predictions.
- `submission.csv`: Template file for submitting predictions to Kaggle.

## Code
The code for this project is organized into Jupyter Notebooks:
- `project-template.ipynb`: Notebook containing exploratory data analysis and feature creation.
                            Notebook for training machine learning models using AutoGluon's Tabular Prediction.
                            Notebook for post-processing predictions to ensure validity.
- `project-template.html`: HTML file of the above notebook 

## Results
The model trained using AutoGluon achieved competitive performance on the Kaggle leaderboard, with a root mean squared error (RMSE) metric indicating the accuracy of predictions.

## Dependencies
The following Python libraries are required to run the code:
- pandas
- numpy
- matplotlib
- seaborn
- AutoGluon

## Acknowledgements
- The dataset for this competition is provided by Kaggle.
- AutoGluon library was used for training machine learning models.
