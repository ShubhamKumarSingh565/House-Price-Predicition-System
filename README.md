# House-Price-Predicition-System

## Introduction

Machine learning has been a major driving force in the past years in several aspects of our lives namely medical diagnosis, normal speech command, detection of an image, product recommendation, spam recognition, and Price prediction, etc. There has been a steep increase in House prices every year, hence an automated system is required to predict future house prices. This system of house price prediction will help the owner to determine the selling price of a house and can help the buyer to arrange the appropriate time to purchase a house. Supervised Learning algorithm namely Linear Regression has been applied in this paper for prediction and analysis of house prices which depends on various factors such as BHK, locality, and bath, etc, and these factors are considered as the independent variables.

![interface](https://user-images.githubusercontent.com/63440492/162664406-0265c598-1cc6-4e5a-9884-1f446308c4e0.png)
------------------------------------------------------------------Fig: Interface Layout------------------------------------------------------------------

## Basic Requirements
- When you run your program on any browser, make sure you have proper network connection because we had use bootstrap in our program to make interface more appealing.
- Make sure your IDE (Pycharm or V S Code) must have install and import some packages listed below:
    * import pandas as pd
    * import numpy as np 
    * from sklearn.model_selection import train_test_split
    * from sklearn.linear_model import LinearRegression,Lasso,Ridge
    * from sklearn.preprocessing import OneHotEncoder, StandardScaler
    * from sklearn.compose import make_column_transformer
    * from sklearn.pipeline import make_pipeline
    * from sklearn.metrics import r2_score
    * import pickle

- Required Datasets link: [House Price Prediction System](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data)
- Colab work that we had attached is just for reference purpose that how we extract data and remove unwanted data [House_Price_Prediction.ipynb](https://github.com/ShubhamKumarSingh565/House-Price-Predicition-System/blob/main/House_Price_Prediction.ipynb)
- Actual data on which we worked using interactive UI through browser is - [Cleaned_data.csv](https://github.com/ShubhamKumarSingh565/House-Price-Predicition-System/blob/main/Cleaned_data.csv)


## Flow Diagram on which our work procced

![diagram-flow](https://user-images.githubusercontent.com/63440492/162669243-438577b5-282f-46d3-abbe-d992d35feebe.png)


## Output Interface 

![prediction](https://user-images.githubusercontent.com/63440492/162668938-26cd9766-b966-4433-9850-8026ea3e8b6d.png)
