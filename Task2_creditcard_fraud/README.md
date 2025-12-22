📌 Credit Card Fraud Detection using Machine Learning
This project focuses on detecting fraudulent credit card transactions using machine learning techniques.
Due to the highly imbalanced nature of fraud data, special care was taken to evaluate models using appropriate metrics.

This project was developed as part of the CodSoft Machine Learning Internship.

📊 Dataset Information

Dataset Name: Credit Card Fraud Dataset

Target Variable: is_fraud

0 → Legitimate transaction

1 → Fraudulent transaction

Total Records: ~5.5 lakh transactions

Challenge: Severe class imbalance (fraud cases are very rare)

🧠 Model & Approach

Baseline Model: Logistic Regression

Improved Model: Logistic Regression with class_weight='balanced'

Why balancing?
To improve recall for fraud cases, which is more important than accuracy in real-world fraud detection.

📈 Model Performance (Balanced Model)

Accuracy: ~90%

Recall (Fraud): ~73%

ROC–AUC Score: ~0.90

In fraud detection, recall is prioritized over accuracy to minimize missed fraud cases.

📊 Confusion Matrix

A confusion matrix was generated to visualize model performance and is saved inside the results/ folder.

🚀 Features

✔ Handles highly imbalanced data
✔ Uses stratified train–test split
✔ Applies feature scaling
✔ Saves trained model and scaler
✔ Evaluation using precision, recall, F1-score, and ROC–AUC