# Fraud_detection_system_credit_card
 Fraud Detection System
A machine learning project that detects fraudulent transactions using the Credit Card Fraud Detection dataset. This project demonstrates preprocessing, handling class imbalance, training a robust model, evaluating it, and providing a command-line interface for real-time transaction prediction.

 Dataset
The dataset used is the Credit Card Fraud Detection dataset, which contains anonymized features (V1–V28), Time, Amount, and a Class label (0 = Legitimate, 1 = Fraud).

🛠 Features
Data preprocessing with scaling and imbalance handling (SMOTE)

Trained using Random Forest Classifier

Model evaluation (Precision, Recall, F1-score)

CLI interface for manual transaction input and fraud prediction

 Requirements
bash
Copy
Edit
pip install pandas numpy scikit-learn imbalanced-learn
