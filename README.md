# Credit Card Fraud Detection
A Machine Learning Model for Detecting Fraudulent Credit Card Transactions

Credit card fraud detection is crucial for safeguarding customers against unauthorized transactions. This project focuses on building a fraud detection model using anonymized transaction data.



## Dataset Overview
The dataset contains credit card transactions made by European cardholders in September 2013. It covers a two-day period and includes both legitimate and fraudulent transactions.

Total Transactions: 284,807
Fraudulent Transactions: 492 (0.172% of all transactions)
Imbalance: The dataset is highly unbalanced, making fraud detection a challenging task.
Features
Anonymized Data: Due to confidentiality, the features have been anonymized (e.g., V1, V2, ... V28).
Time and Amount: These are the only non-anonymized features in the dataset.
Getting Started

Follow the steps below to set up the project and run the model:

## 1. Clone the Repository
'''
git clone https://github.com/iam-harsha-vardhan/Credit-card-fraud-detection
'''

cd Credit-Card-Fraud-Detection

## 2. Download the Dataset
Download the dataset from Kaggle.
Unzip the file and place creditcard.csv in the main project folder.

## 3. Install Dependencies
Install the required Python packages using pip:

pip install -r requirements.txt

## 4. Run the Jupyter Notebook
Launch Jupyter Notebook and open the project notebook. Execute the cells to train and evaluate the fraud detection model.

jupyter notebook

