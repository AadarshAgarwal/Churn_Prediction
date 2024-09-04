# Churn Prediction Project

## Introduction

Churn prediction plays a crucial role in identifying key patterns and aiding in customer retention efforts. In this project, I used a real-world dataset containing over 250 features and more than 1 million user records.

Two important variables in this analysis are OP (Observation Period) and CP (Churn Period). During the OP, user data is collected to understand their behavior patterns. For instance, I track the user's activities during this period. The CP represents the time window in which churn is determined. If the user opens the app during the CP, they are classified as "no churn"; otherwise, they are considered to have churned.

## ML Algorithms

- Random Forest Classifier
- XgBoost
- Logistic Regression

## Results

In churn prediction, recall is the most critical metric because our goal is to identify all potential churns, even if it means incorrectly classifying a few non-churns as churns. This approach allows us to provide churn prevention efforts to all at-risk users. I achieved a recall rate of 0.7, which is impressive given the complexity of the real-world dataset
