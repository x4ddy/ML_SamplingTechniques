# Sampling Techniques on Imbalanced Credit Card Dataset

## Overview
- Analyzes the impact of different sampling techniques on machine learning models
- Uses a credit card fraud detection dataset
- Focuses on handling severe class imbalance

## Dataset
- Class 0: Non-fraudulent transactions
- Class 1: Fraudulent transactions
- Dataset is highly imbalanced

## Handling Class Imbalance
- Split data into majority and minority classes
- Minority class upsampled using random sampling with replacement
- Final dataset balanced to ensure fair model training

## Sampling Techniques
- Random Holdout Sampling  
- Stratified Holdout Sampling  
- Bootstrap Sampling  
- K-Fold Sampling (Single Fold)  
- Stratified K-Fold Sampling (Single Fold)

## Machine Learning Models
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)

## Evaluation
- Feature scaling using StandardScaler
- Models trained on training set and tested on unseen data
- Accuracy used as performance metric
- Results compared using tables and bar graphs

## Key Takeaways
- Sampling strategy significantly affects model performance
- No single sampling method works best for all models
- Proper data balancing is critical for reliable results
