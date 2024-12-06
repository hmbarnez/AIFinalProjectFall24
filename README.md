## Abstract <br>
Purchasing a car represents a significant financial decision for individuals, requiring accurate pricing to ensure informed transactions for both buyers and sellers. However, many buyers often fail to adequately research the factors influencing car prices, 
such as make, model, year, and mileage, leading to suboptimal outcomes. This study presents the development of an AI model designed to predict car prices with high accuracy, using various vehicle attributes to assist users in making data-driven decisions.
<br>
Our AI model was trained to predict car prices using a dataset from Kaggle, a website hosting a vast repository of datasets that are often used to perform data analysis, visualization, and machine learning. 
## Project Description
This project is a predictive model for estimating used car prices using a deep learning approach built with TensorFlow and Keras. It involves data preprocessing, neural network model training, and hyperparameter tuning. The model is designed to handle various data processing techniques including label encoding, one-hot encoding, and feature scaling.

## Dataset 
This is the original [dataset](used_cars.csv) we attempted to use 
<br>
This is the [dataset](used_cars_clean.csv) we ended up using

## Regressor Tests
This is the failed [Regressor Test](XGBoostTest.ipynb) <br>
This is the [Regressor Test](UsedCarXGBRegressor.ipynb) that worked

## Neural Network Test
This is our [Neural Network](UsedCarNeuralNetworkTest.ipynb) test for our failed dataset <br>
This is our [Neural Network](UsedCarNeuralNetwork.ipynb) test for our current dataset

## Data collection
The first step to beginning the project was to select a dataset from Kaggle with the most looked at attributes when purchasing a car such as:
Make: The brand of the car (e.g., Toyota, Honda)
Model: The specific model of the car (e.g., Camry, Civic)
Year: The manufacturing year of the car
Mileage: The number of miles the car has been driven
Other characteristics: Features such as engine size, fuel type, color, number of doors, etc..

## Data Preprocessing
Before the model could be trained, we had to clean and transform the dataset into a useful format. This process involved:
Handling missing values: Any features missing data were either filled in or removed.
Encoding categorical variables: For features like make and model which are categorical, the data needed to be converted into numerical values using >>>>>>

## Model selection

We decided to create two machine learning algorithm models : An Xgboost and a Neural network. An Xgboost Regressor which is a supervised machine learning algorithm designed for regression tasks where the goal is to predict a continually fluctuating variable. It is a scalable and efficient implementation fo the gradient boosting method and is known for its high speed, accuracy and flexibility. A neural network model is a type of machine learning model inspired by the function of the human brain. It is highly effective in recognizing patterns, approximations and deriving solutions to problems based on previous data.


