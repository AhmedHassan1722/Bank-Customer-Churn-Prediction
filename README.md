🏦 Bank Customer Churn Prediction
📌 Overview

This project implements an end-to-end machine learning pipeline to predict customer churn in a banking dataset. The objective is to identify customers likely to leave the bank and support data-driven retention strategies.

The workflow covers data preprocessing, exploratory data analysis, handling class imbalance, model benchmarking using stratified cross-validation, neural network training, and generation of Kaggle-compatible submissions.

🧠 Key Highlights

Robust preprocessing pipeline with encoding and normalization

Class imbalance handling using SMOTE

Stratified K-Fold cross-validation for fair model evaluation

Benchmarking of multiple machine learning algorithms

Neural network optimized using ROC-AUC

Automatic generation of Kaggle submission files

🧪 Models Evaluated

Logistic Regression

Random Forest Classifier

Support Vector Classifier (SVC)

XGBoost Classifier

K-Nearest Neighbors (KNN)

Naive Bayes

Deep Neural Network (Keras + Early Stopping)

📊 Evaluation Metrics

Models are evaluated using:

Accuracy

Recall

F1-Score

ROC-AUC

Confusion Matrix

Stratified cross-validation ensures stable and unbiased performance comparison across imbalanced classes.

🔁 Workflow

Load and inspect training and test datasets

Encode categorical features (Geography, Gender)

Normalize numerical features using Min-Max Scaling

Analyze feature correlations

Apply SMOTE to balance classes

Evaluate classical ML models with Stratified K-Fold CV

Train and optimize a neural network

Select the best performing model

Generate Kaggle-ready submission.csv

🛠️ Technologies Used

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Imbalanced-learn (SMOTE)

XGBoost

TensorFlow / Keras

📁 Output

submission.csv — ready for Kaggle submission

🚀 Future Improvements

Hyperparameter tuning with Optuna / GridSearchCV

Feature importance and SHAP analysis

Model ensembling and stacking

Probability threshold optimization
