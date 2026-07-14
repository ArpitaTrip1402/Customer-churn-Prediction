# Customer Churn Prediction using Ensemble Learning

## 📌 Project Overview

Customer churn prediction helps businesses identify customers who are likely to discontinue using their services.
Early identification enables companies to implement targeted retention strategies, improve customer satisfaction, and 
reduce revenue loss.

This project builds a machine learning model to predict customer churn by comparing the performance of multiple classification
algorithms. The models are evaluated using standard classification metrics, and the best-performing model is selected.

## 🎯 Objectives

* Analyze customer data to understand factors influencing churn.
* Preprocess and prepare the dataset for machine learning.
* Train multiple classification models.
* Compare model performance using evaluation metrics.
* Select the best model for customer churn prediction.

## 📂 Dataset

The project uses a customer churn dataset containing customer demographics, account information, and service usage details.

Typical features include:

* Gender
* Senior Citizen
* Partner
* Dependents
* Tenure
* Internet Service
* Contract Type
* Monthly Charges
* Total Charges
* Payment Method
* Paperless Billing
* Churn (Target Variable)

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Imbalanced-learn (SMOTE)
* Jupyter Notebook

## 📊 Project Workflow

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Handling Missing Values
5. Encoding Categorical Features
6. Feature Scaling (where applicable)
7. Handling Class Imbalance using SMOTE
8. Train-Test Split
9. Model Training
10. Model Evaluation
11. Model Comparison
12. Best Model Selection

## 🤖 Models Implemented
* Decision Tree Classifier
* Random Forest Classifier
* XGBoost Classifier

## 📈 Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Classification Report


Open **Churn_Prediction.ipynb** and run all cells.

## 📌 Future Improvements

* Deploy the model using Streamlit.
* Hyperparameter tuning using GridSearchCV or RandomizedSearchCV.
* Feature importance visualization.
* Experiment with additional ensemble methods.
* Build a real-time churn prediction web application.

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

* Data preprocessing
* Exploratory Data Analysis
* Handling class imbalance using SMOTE
* Ensemble Learning
* Model evaluation and comparison
* Customer churn prediction
* Building end-to-end machine learning workflows

