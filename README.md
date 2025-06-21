# App Rating Prediction Project
This project aims to predict the user rating of mobile applications using a dataset of app-related features. The goal is to build a regression model that accurately estimates ratings based on factors like app size, number of installs, price, and more.

🔍 Objective
To develop a machine learning model that predicts app ratings from various app store features, and generate a valid submission file for a competitive evaluation (e.g., Kaggle-style).

🛠️ Tools & Technologies
Python, Pandas, NumPy

Scikit-learn for preprocessing, scaling, and modeling

Linear Regression with cross-validation

Data visualization and transformation techniques (e.g., log1p, feature engineering)

🔧 Key Steps
Data Cleaning

Converted app sizes and prices into numeric formats

Handled missing and inconsistent values

Feature Engineering

Created log-scaled features (e.g., installs, size, price)

Added interaction features like size per install and price per install

Modeling

Applied linear regression

Evaluated performance using 5-fold cross-validation (CV RMSE ≈ 0.73)

Prediction & Submission

Generated predictions on test data

Created a submission.csv file for competition evaluation

📈 Results
Achieved a CV Root Mean Squared Error (RMSE) of approximately 0.73

Created a clean and reusable machine learning pipeline
