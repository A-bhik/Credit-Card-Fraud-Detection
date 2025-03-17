# Credit-Card-Fraud-Detection
Overview:-

This project focuses on developing a classification model to detect fraudulent credit card transactions efficiently. The dataset includes transaction details such as amount, merchant information, and timestamps. The model is designed to minimize false positives while ensuring high accuracy.

Objectives:-

Develop a machine learning model to detect fraud.

Address class imbalance using oversampling, undersampling, or synthetic data generation.

Engineer meaningful features such as transaction frequency, location mismatch, and spending patterns.

Evaluate model performance using appropriate metrics.

Ensure the model is optimized for high accuracy with minimal false positives.

Dataset:-

The dataset contains:

Time: Seconds elapsed between the transaction and the first transaction in the dataset.

Setup & Installation

1.Clone the repository:
cd Credit-Card-Fraud-Detection
2.Install dependencies:
pip install -r requirements.txt
3.Run preprocessing:
python src/preprocessing.py
4.Train the model:
python src/train.py
5.Evaluate the model:
python src/evaluate.py


Model & Techniques Used:-

Feature Engineering: Transaction frequency, spending patterns, location verification.

Class Imbalance Handling: Oversampling (SMOTE) and undersampling.

Machine Learning Models:

Logistic Regression

Random Forest

XGBoost

Evaluation Metrics:

Precision, Recall, F1-score

AUC-ROC Curve

Results

The best model achieved:

High Precision to minimize false positives.

Strong Recall to detect fraud cases effectively.

Optimized F1-score for overall balance.

Class: The target variable (0 for non-fraudulent, 1 for fraudulent transactions
