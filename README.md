# Fraud_detection_system_credit_card
 Fraud Detection System
A machine learning project that detects fraudulent transactions using the Credit Card Fraud Detection dataset. This project demonstrates preprocessing, handling class imbalance, training a robust model, evaluating it, and providing a command-line interface for real-time transaction prediction.

 Dataset
The dataset used is the Credit Card Fraud Detection dataset, which contains anonymized features (V1–V28), Time, Amount, and a Class label (0 = Legitimate, 1 = Fraud).
link of dataset:
"https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data"
 Features
Data preprocessing with scaling and imbalance handling (SMOTE)

Trained using Random Forest Classifier

Model evaluation (Precision, Recall, F1-score)

CLI interface for manual transaction input and fraud prediction


 Requirements

pip install pandas numpy scikit-learn imbalanced-learn

How to Run
Place the dataset (creditcard.csv) in the same directory as the script/  or place the directory location of file 

Run the script:

download the python fraud_detection_system_credit_card.py
Sample Output:

Enter values for a new transaction (30 features as comma-separated values):
Paste values:
0.1, -1.3, 2.5, ..., 99.00

Prediction: Legitimate Transaction / Fradulent
