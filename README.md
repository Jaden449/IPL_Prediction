IPL Match Winner Prediction

Overview

Predicting the outcome of an Indian Premier League (IPL) match using machine learning and data analysis. This project processes historical IPL match data, extracts key features, and applies machine learning models to predict match results based on various in-game parameters.

Features

Data preprocessing and feature engineering from IPL datasets

Handling missing values and normalizing team names for consistency

Calculation of crucial match metrics (e.g., Current Run Rate (CRR), Required Run Rate (RRR), wickets left, balls left, etc.)

Application of machine learning techniques such as Logistic Regression and Random Forest Classifier

Performance evaluation using accuracy scores and probability predictions

Interactive match progression analysis for insights

Dataset

The project utilizes historical IPL match data from CSV files containing:

Match details (teams, location, winner, scores, etc.)

Ball-by-ball delivery data

Model Implementation

Preprocessing: Encoding categorical features (teams, venues), handling missing data

Feature Selection: Runs left, balls left, wickets, total runs, CRR, RRR

Training: Logistic Regression model using sklearn.pipeline for data transformation and classification

Evaluation: Achieves ~80% accuracy in predicting match outcomes

Probability Prediction: Determines winning probability at different match stages
