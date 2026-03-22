Heart Disease Risk Factor Analysis and Prediction Using Machine Learning
Project Overview
This project focuses on analyzing key medical factors that contribute to heart disease and building machine learning models to predict the likelihood of heart disease.
The goal is to identify important risk factors and develop a predictive model that can assist in early detection.

Objectives
Perform Exploratory Data Analysis (EDA) on healthcare data
Identify key risk factors influencing heart disease
Build machine learning models for prediction
Compare model performance
Visualize insights using graphs and dashboards

Tools & Technologies
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook
Power BI (for dashboard)

Dataset
The dataset used in this project consists of training and testing data:
📁 Train Data: Included in this repository (data/train.csv) 🔗 Test Data: Hosted externally due to file size limitations [https://drive.google.com/file/d/13nHnNMn_GusosqLL8KLBrxEzaaahgw34/view?usp=sharing] The dataset contains medical attributes such as:
Age
Sex
Chest Pain Type
Blood Pressure
Cholesterol
Maximum Heart Rate
Exercise Induced Angina
ST Depression
Number of Vessels
Thallium Test Results
Heart Disease (Target Variable)

Project Workflow
Data Collection
Data Cleaning
Data Preprocessing
Exploratory Data Analysis (EDA)
Feature Engineering
Train-Validation Split
Feature Scaling
Model Training
Model Evaluation
Prediction on Test Data
Feature Importance Analysis

Machine Learning Models Used
Logistic Regression
Random Forest Classifier
K-Nearest Neighbors (KNN)

Key Insights
Age is a significant factor influencing heart disease risk
High cholesterol levels are associated with increased risk
Exercise-induced angina strongly correlates with heart disease
Maximum heart rate shows an inverse relationship with risk

Results
Accuracy: 88.36%
Compared multiple machine learning models
Random Forest achieved the best performance
Model successfully predicts presence/absence of heart disease

Project Structure
Heart-Disease-Risk-Factor-Analysis
│
├── data
├── notebook
├── images
├── dashboard
├── README.md
└── requirements.txt

