# Insurance Premium Prediction App

## Overview

The Insurance Premium Prediction App is a Machine Learning web application that predicts the insurance premium amount based on user details such as age, BMI, number of children, smoking status, gender, and region.

The application uses a Linear Regression model* trained on the insurance dataset and provides predictions through an interactive Streamlit web interface.

## Problem Statement

Insurance companies calculate premium amounts based on several factors like age, lifestyle, and health indicators. The goal of this project is to build a *machine learning model that predicts insurance premiums* based on these attributes.

## Dataset

The project uses the *Insurance dataset*, which contains the following features:

* age – Age of the individual
* sex – Gender of the individual
* bmi – Body Mass Index
* children – Number of dependents
* smoker – Whether the individual is a smoker or not
* region – Residential region
* charges – Medical insurance premium (Target Variable)

## Machine Learning Model

This project uses the Linear Regression algorithm to predict insurance charges.

### Model Workflow

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing
4. Feature Encoding using OneHotEncoder
5. Feature Scaling using StandardScaler
6. Model Training using Linear Regression
7. Model Saving using Joblib/Pickle
8. Deployment using Streamlit

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit
* Joblib / Pickle

## Project Structure

InsuranceApp
│
├── app.py                 # Streamlit application
├── LR_model.pkl           # Trained Linear Regression model
├── scaler.pkl             # Feature scaling object
├── onehotencoder.pkl      # Encoder for categorical variables
├── requirements.txt       # Required libraries
└── README.md              # Project documentation



## How the Application Works

1. The user enters the following inputs in the Streamlit interface:

   * Age
   * BMI
   * Number of Children
   * Gender
   * Smoking Status
   * Region

2. The input data is processed using the saved encoder and scaler.

3. The processed data is passed to the trained Linear Regression model.

4. The model predicts the estimated insurance premium.

## Streamlit Web Application

The project includes an interactive *Streamlit UI* that allows users to input their details and get an instant insurance premium prediction.

## Live Application

You can access the deployed Streamlit application here:

*Streamlit App URL:*
https://insuranceapp-sravya.streamlit.app/

## Future Improvements

* Train multiple regression models and compare performance
* Improve prediction accuracy
* Enhance the user interface
* Add data visualization dashboards

## Author

*Sravya Pitani*
Machine Learning Enthusiast



