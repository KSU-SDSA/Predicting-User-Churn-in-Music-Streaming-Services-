Predicting Customer Churn in a Music Streaming Service
Welcome to this churn prediction project! This repository explores how to predict whether a user will cancel their subscription to a music streaming platform, based on their interaction history and behavior.

Project Overview
In the competitive world of music streaming, retaining users is critical. This project aims to identify users at risk of churning, i.e., those who are likely to cancel their subscription. With that insight, companies can take proactive steps to improve user engagement and retention.

We worked with a massive dataset (26M+ events) from a fictional music streaming service, and trained multiple machine learning models to classify users into churned vs active.

 Dataset
Size: ~26 million user interaction logs

Users: 22,278 unique users

Features: 18 total, including session behavior, location, browser agent, and more

Target: Binary label indicating whether a user churned (visited the cancellation confirmation page)

 Key Steps
1.  Data Cleaning & Preparation
Handled large-scale event log data (12.5GB)

Defined churn based on user actions

Aggregated user-level features for modeling

2.  Exploratory Analysis
Calculated churn rate: 22.46%

Identified behavioral patterns linked to churn

Performed user segmentation via Gaussian Mixture Models (GMM)

3.  Modeling
We trained and evaluated the following models:

Logistic Regression

Random Forest

XGBoost

LightGBM

Metrics used:

Accuracy

Precision / Recall / F1

ROC AUC Score

 Best Model: LightGBM
Metric	Score
Accuracy	86%
Precision	0.64
Recall	0.80
F1-Score	0.71
ROC AUC	0.904 
LightGBM achieved the best balance of performance and speed, and it's our recommended model for production deployment.
