# Credit-card-fraud-detection
A machine learning–based credit card fraud detection system built using Python and Random Forest. The project preprocesses transaction data, handles class imbalance, and predicts fraudulent transactions with high accuracy.

![creditcard](https://github.com/user-attachments/assets/fa645c57-c8b6-4954-86be-78ba925d6ba4)


# Credit Card Fraud Detection using Machine Learning

This project implements a machine learning–based credit card fraud detection system using Python and Scikit-learn. The goal is to identify fraudulent transactions from real-world credit card transaction data.

## Features
- Data preprocessing and cleaning
- Handling missing values using mean imputation
- Feature scaling using StandardScaler
- Fraud detection using Random Forest Classifier
- Evaluation using Precision, Recall, F1-score, and ROC-AUC
- Model saving for future deployment

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn


## Dataset
- Credit Card Fraud Detection Dataset
- Target variable: **Class**
  - `0` → Legitimate transaction
  - `1` → Fraudulent transaction

⚠️ The dataset You can download it from Kaggle:
> Credit Card Fraud Detection Dataset

---

## How to Run the Project

1. Clone the repository:
```bash
git clone https://github.com/your-username/credit-card-fraud-detection.git
Install dependencies:
pip install -r requirements.txt
Place creditcard.csv in the project folder
Run the script:
python fraud_detection.py
Model Evaluation
Confusion Matrix
Classification Report
ROC-AUC Score
--> Applications
Banking fraud detection
Financial transaction monitoring
Risk management systems

--> License
This project is licensed under the MIT License.
