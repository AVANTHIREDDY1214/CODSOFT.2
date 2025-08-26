Customer Churn Prediction

This repository contains an end-to-end machine learning project for predicting customer churn, completed as part of an internship provided by CodSoft. The goal is to build predictive models that help businesses identify customers who are likely to leave, enabling proactive retention strategies.

📂 Dataset

The dataset used is Churn_Modelling.csv, which includes features such as customer demographics, account information, and activity metrics. The target variable is:

Exited – indicates whether a customer has churned (1) or not (0).

🛠 Project Overview

The project follows a complete machine learning pipeline:

Data Loading & Exploration

Check dataset shape and preview data.

Data Preprocessing

Encode categorical variables using LabelEncoder.

Split dataset into training and testing sets.

Scale features using StandardScaler.

Modeling

Built and evaluated three models:

Logistic Regression

Random Forest Classifier

Gradient Boosting Classifier

Evaluation

Classification report

Confusion matrix

ROC-AUC scores

Feature Importance

Visualize feature importance using Random Forest.

🧰 Technologies Used

Python

Pandas & NumPy

Scikit-learn

Matplotlib

🚀 How to Run

Clone the repository:

git clone <repo>


Install dependencies (if not already installed):

pip install -r requirements.txt


Run the notebook or Python script:

python churn_prediction.py

📊 Results

Logistic Regression, Random Forest, and Gradient Boosting models were trained and evaluated.

Feature importance analysis highlights which factors contribute most to customer churn.

📝 Conclusion

This project demonstrates a complete workflow for building a predictive model for customer churn, from data preprocessing to model evaluation and visualization. It provides practical insights into machine learning for business analytics.

📌 Acknowledgment

Project completed as part of CodSoft internship program.
