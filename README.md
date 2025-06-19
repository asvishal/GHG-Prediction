🌍 GHG Emission Prediction using Machine Learning

This project aims to predict greenhouse gas (GHG) emissions from various agricultural commodities using historical data and machine learning techniques. The goal is to build an accurate, interpretable, and future-ready forecasting model that supports climate policy planning and sustainable agriculture.



🚀 Project Highlights

* 📁 Data Source: GHG emission data from 2010 to 2016, extracted from an Excel file.
* 📊 Features Used: Year, Commodity Code, Commodity Name
* 🎯 Target Variable: Total GHG Emissions (in CO₂-equivalent tonnes)
* 🧠 Model Used: Random Forest Regressor for robust and interpretable predictions
* 🔮 Forecasting: Simulated emissions for future years (2017–2020)
* 📈 Dashboard: Interactive emissions simulator built with `ipywidgets` for notebook-based exploration
* 🧪 Evaluation Metrics: RMSE, R² score



🛠️ Pipeline Overview

1. Data Cleaning & Preprocessing

   * Handled missing values and encoded categorical features using `LabelEncoder`.

2. Exploratory Data Analysis (EDA)

   * Used `matplotlib` and `seaborn` to understand emission trends across years and commodities.

3. Model Training

   * Split data into training/testing sets.
   * Trained a `RandomForestRegressor` to model GHG emissions.

4. Model Evaluation

   * Evaluated predictions using RMSE and R² score.

5. Emission Forecasting

   * Generated synthetic inputs for 2017–2020.
   * Predicted future GHG emissions using the trained model.

6. Interactive Dashboard

   * Implemented a Kaggle-compatible dashboard using `ipywidgets` to:

     * View predictions by year/commodity
     * Simulate emission changes using a % slider
     * Visualize emission shifts using bar plots

7. Model and Output Saving

   * Saved the trained model and prediction results for further use and visualization.



📂 Files Included

* `ghg_rf_model.pkl`: Trained ML model
* `future_ghg_predictions.csv`: Forecasted emission data (2017–2020)
* `ghg-prediction-own.ipynb`: Interactive notebook-based dashboard




📌 Use Cases

* Climate impact assessment of different commodities
* Policy modeling for sustainable agriculture
* Educational tool for environmental data science


