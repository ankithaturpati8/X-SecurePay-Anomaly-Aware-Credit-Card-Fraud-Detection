# X-SecurePay: Anomaly-Aware Credit Card Fraud Detection

## Overview
X-SecurePay is a machine learning project developed to detect fraudulent credit card transactions. The project combines anomaly detection, classification, and explainable AI techniques to improve fraud detection performance and model interpretability.

## Technologies Used
- Python
- TensorFlow (Autoencoder)
- XGBoost
- SHAP
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Imbalanced-learn (SMOTETomek)

## Features
- Data preprocessing and feature engineering
- Class imbalance handling using SMOTETomek
- Fraud detection using TensorFlow Autoencoder and XGBoost
- Model explainability using SHAP
- Performance evaluation using classification metrics

## Dataset
This project uses the publicly available **Credit Card Fraud Detection Dataset**, containing anonymized transaction records for fraud classification.

## Project Workflow
1. Load and preprocess the dataset.
2. Handle class imbalance using SMOTETomek.
3. Train the TensorFlow Autoencoder.
4. Train the XGBoost classifier.
5. Evaluate model performance.
6. Interpret predictions using SHAP.

## Results
The model was evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Score
- SHAP Feature Importance

## Research Publication

This project was presented at the **Global Conference on Computational Mathematics and Intelligent Engineering Applications (GCCMIEA-2025)**.

📄 **Publication:** [View Research Paper](X-SecurePay-Publication.pdf)
