# Loan Approval Prediction

This project predicts whether a loan application will be approved using Machine Learning. It uses classification models, feature engineering, hyperparameter tuning, and ensemble methods for high accuracy.

## Features

- Preprocessing: handles missing data, encodes categorical features, scales numeric features
- Models: Logistic Regression, Decision Tree, Random Forest, Gradient Boosting
- Hyperparameter tuning with GridSearchCV
- Ensemble: Voting Classifier for improved accuracy
- Feature importance visualization
- Save and load trained model
- Predict new applicant data using a simple function

## How to Use

1. Clone the repository
2. Put your dataset in `data/loan_data.csv`
3. Train the model:  
   ```bash
   python src/train_model.py
