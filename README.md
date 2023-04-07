# NYC-Taxi-Trip-Time-prediction-ML-regression-
Predicting total ride duration of taxi trips in New York City ( Almabetter capstone project on ML Regression)
Taxi Trip Time Prediction
This is a machine learning regression project to predict the total ride duration of taxi trips in New York City. The project is based on the New York City Taxi Trip Duration dataset from Kaggle, which includes information about the pickup and dropoff locations, as well as other features such as the pickup and dropoff times, the passenger count, and the distance between the locations.

Project Goal
The goal of this project is to build a machine learning model that can accurately predict the total ride duration of taxi trips in New York City based on the given features. This can be useful for both taxi drivers and passengers to estimate the trip duration and plan their schedules accordingly.

Dataset
My drive link for dataset download - https://drive.google.com/file/d/1khjo_prBBzJEBLcipOl8pTMp9tZrVmz2/view?usp=sharing
The dataset can be downloaded from Kaggle using the following link: https://www.kaggle.com/c/nyc-taxi-trip-duration/data

It consists of two CSV files: train.csv and test.csv. The train.csv file contains the training data, which includes the actual trip durations. The test.csv file contains the test data, which does not include the trip durations and is used for model evaluation.

Data Preprocessing
Before building the machine learning model, the data needs to be preprocessed to clean and transform it into a format that can be used for training the model. This includes handling missing values, converting categorical features into numerical ones, and scaling the features if necessary.

Feature Engineering
In addition to preprocessing, feature engineering is also performed to create new features that can help improve the accuracy of the model. This includes extracting information from the pickup and dropoff times, calculating the distance between the locations, and creating new categorical features based on the pickup and dropoff neighborhoods.

Machine Learning Model
The machine learning model used for this project is a regression model, which predicts the continuous output variable of trip duration. Several regression algorithms such as linear regression, decision tree regression, random forest regression, gradient boosting regression are experimented to choose the best performing model.

Model Evaluation
The performance of the machine learning model is evaluated using the root mean squared error (RMSE) metric on the test set. This metric measures the average distance between the predicted and actual trip durations.

Requirements
This project requires Python 3.6 or later, as well as the following libraries:

pandas
numpy
matplotlib
seaborn
scikit-learn
Usage
To run the project, simply clone the repository and run the main.py file. The script will preprocess the data, perform feature engineering, train the machine learning model, and evaluate its performance on the test set. The predicted trip durations for the test set will also be saved in a CSV file.

Conclusion

By predicting the total ride duration of taxi trips in New York City, this project can be helpful for both taxi drivers and passengers to estimate trip durations and plan their schedules accordingly. The machine learning model can be further improved by including additional features or using more advanced algorithms.
