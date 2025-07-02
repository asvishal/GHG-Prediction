🌍 GHG Emission Prediction using Machine Learning

This project aims to predict greenhouse gas (GHG) emissions from various agricultural commodities using historical data and machine learning techniques. The goal is to build an accurate, interpretable, and future-ready forecasting model that supports climate policy planning and sustainable agriculture.

🚀 Project Highlights

Goal: Predict and analyze GHG emissions based on country-level features.

Data: A dataset containing GHG emissions and related features for countries from 2010 to 2016.

Tech Stack: Python, Pandas, Scikit-learn, XGBoost, Plotly, Streamlit

🔍 Features
Data Cleaning & Preprocessing:

Handled missing values

Label and one-hot encoding of categorical variables

Feature scaling

Exploratory Data Analysis (EDA):

Correlation heatmaps

Feature distributions

Temporal emission trends

Machine Learning Models:

Linear Regression

Random Forest Regressor

XGBoost Regressor

Model comparison using RMSE and R² Score

Forecasting:

Predicting future GHG emissions based on learned patterns

Interactive Dashboard:

Streamlit-powered app for user-friendly exploration and prediction

Data Cleaning & Preprocessing

Handled missing values and encoded categorical features using LabelEncoder.

Exploratory Data Analysis (EDA)

Used matplotlib and seaborn to understand emission trends across years and commodities.

Model Training

Split data into training/testing sets. Trained a RandomForestRegressor to model GHG emissions.

Model Evaluation

Evaluated predictions using RMSE and R² score.

Emission Forecasting

Generated synthetic inputs for 2017–2020. Predicted future GHG emissions using the trained model.

Interactive Dashboard

Implemented a Kaggle-compatible dashboard using ipywidgets to:

View predictions by year/commodity Simulate emission changes using a % slider Visualize emission shifts using bar plots

Model and Output Saving

Saved the trained model and prediction results for further use and visualization.


📌 Use Cases

Climate impact assessment of different commodities
Policy modeling for sustainable agriculture
Educational tool for environmental data science
