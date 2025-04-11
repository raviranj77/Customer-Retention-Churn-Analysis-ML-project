# Customer-Retention-Churn-Analysis-ML-project
Predict customer churn using ML models like Random Forest &amp; XGBoost. Helps businesses retain at-risk customers with data-driven insights.
🧠 Customer Churn Prediction using Machine Learning

This project focuses on predicting customer churn for a telecom company using machine learning algorithms like Random Forest, Decision Tree, and XGBoost. The goal is to help businesses retain customers by identifying churn risk early.

📂 Project Structure

 → Contains the original dataset (**)

 → Python script for preprocessing, modeling, evaluation**

 → Saved model & encoders**

 → Visualizations like churn probability graphs**

 → Project overview**

 → Python dependencies**

🔍 Problem Statement

Customer churn is a critical problem for telecom companies. This project builds a model to:

Analyze customer behavior

Predict churn probabilities

Help take preventive actions to retain high-risk customers

📊 Key Steps

Data Cleaning: Removed customer ID, handled missing values in ``.

EDA: Visualized feature distributions, correlations, class imbalance.

Preprocessing: Label encoding, SMOTE for balancing.

Modeling: Trained Random Forest, Decision Tree & XGBoost.

Evaluation: Accuracy, confusion matrix, classification report.

Prediction System: Built a system to predict churn for new customers.

Saved Models: Stored model & encoders using pickle.

💡 Results

Random Forest gave the best accuracy.

The final model is saved in ``.

🛠️ Tech Stack

Python, Pandas, NumPy, Seaborn, Matplotlib

Scikit-learn, XGBoost, Imbalanced-learn (SMOTE)

Pickle for model serialization

