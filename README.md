# 🏏 India vs New Zealand T20 Score Prediction using Machine Learning

## Project Overview

This project predicts the final T20 cricket score based on the current match situation using Machine Learning.
The model analyzes match conditions such as overs, wickets, run rate, and balls remaining to estimate the final score at the end of 20 overs.

The project simulates India vs New Zealand T20 match scenarios and applies machine learning techniques to forecast the final score.

This type of predictive system can be useful for:

Cricket analytics

Sports broadcasting insights

Match strategy analysis

Data science portfolio projects

## Dataset Information

The dataset is a synthetic cricket match dataset representing ball-by-ball match situations.

Features used in the dataset
Feature	Description
match_id	Unique match identifier
venue	Match venue
inning	Current innings
over	Current over
ball	Ball number
runs	Runs scored
wickets	Wickets fallen
total_runs	Current total score
balls_remaining	Balls left in the innings
current_run_rate	Current run rate
powerplay	Whether the powerplay is active

These variables help the model understand match progress and scoring patterns.

## Machine Learning Workflow

The project follows a complete Data Science pipeline:

1️⃣ Data Preprocessing

Load dataset

Handle categorical features

Feature selection

Data cleaning

2️⃣ Exploratory Data Analysis (EDA)

Understanding scoring patterns

Run rate trends

Wickets vs scoring relationship

3️⃣ Feature Engineering

Important match situation features:

Current score

Overs completed

Wickets fallen

Current run rate

Balls remaining

4️⃣ Model Training

Machine learning models are trained to predict final score.

Examples include:

Linear Regression

Random Forest Regressor

Decision Tree Regressor

5️⃣ Model Evaluation

Models are evaluated using metrics like:

Mean Absolute Error (MAE)

## Technologies Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Jupyter Notebook

## Future Improvements

Add Live Match Score Prediction

Deploy using Streamlit Web App

Use Deep Learning models

Train using real IPL / T20 datasets
