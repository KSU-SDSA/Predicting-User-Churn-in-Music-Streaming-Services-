# Customer Churn Prediction and Analysis
This project aims to analyze and predict customer churn using a combination of unsupervised clustering, advanced feature engineering, and machine learning models. It provides actionable insights for business retention strategies by identifying at-risk customer segments and evaluating model performance using ROC-AUC scores.

# Key Features
Data Loading & Cleaning: Processes JSON event log data efficiently.

Exploratory Data Analysis (EDA): Identifies trends, outliers, and churn behavior patterns.

Feature Engineering: Extracts user behavior metrics such as session frequency, listening duration, song/artist diversity, and membership details.

Clustering Analysis: Segments users using Gaussian Mixture Models (GMM) for behavioral insights.

Modeling & Hyperparameter Tuning: Trains and tunes models including Logistic Regression, Random Forest, XGBoost, and LightGBM.

Top Feature Selection: Identifies top predictive features to improve model efficiency.

Model Evaluation: Uses ROC-AUC to assess final model performance.

Business Recommendations: Derives actionable recommendations based on churn risk per cluster and top features.

# Visualizations
Class imbalance distribution

Cluster characteristics and churn rates

Correlation heatmaps

ROC curves for model comparison

# Models Used
Logistic Regression

Random Forest

XGBoost

LightGBM

# Output
Trained models and evaluation metrics

Cluster interpretation report

Business recommendations based on churn drivers

Saved plots for inclusion in presentations or dashboards
