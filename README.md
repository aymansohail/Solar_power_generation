# Solar Power Generation Prediction using Machine Learning

A machine learning-based project designed to predict solar power generation using environmental and atmospheric parameters. The project focuses on building an accurate regression model to estimate power output, helping improve renewable energy planning and operational efficiency.

## Overview

This project uses historical solar plant data and weather-related features such as temperature, humidity, wind speed, pressure, visibility, and sky cover to forecast solar power generation. The workflow includes data preprocessing, exploratory data analysis, feature engineering, model training, performance evaluation, and deployment through a user-friendly web application.

## Features

* Data preprocessing and missing value handling
* Exploratory Data Analysis (EDA) with visual insights
* Correlation analysis for feature relationships
* Multiple regression model implementation and comparison
* Model evaluation using MAE, RMSE, and R² Score
* Feature importance analysis for interpretability
* Deployment-ready Streamlit application for real-time prediction

## Tech Stack

* **Programming Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Joblib
* **Deployment:** Streamlit, Ngrok

## Machine Learning Models Used

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Gradient Boosting Regressor

## Results

Among all tested algorithms, **Gradient Boosting Regressor** delivered the best predictive performance with the highest R² score and balanced error metrics. Feature importance analysis revealed the most influential environmental factors affecting solar energy output.

## Project Impact

This project demonstrates how machine learning can support sustainable energy solutions by improving solar power forecasting accuracy. It provides a scalable framework that can be adapted for smart grid systems and renewable energy optimization.

## Future Enhancements

* Integration with live weather APIs for dynamic forecasting
* Deployment on cloud platforms for wider accessibility
* Expansion into deep learning models for higher prediction accuracy

## Repository Purpose

This repository serves as a complete end-to-end machine learning solution, from raw data analysis to deployment, showcasing practical AI applications in renewable energy.
