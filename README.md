# onlinefrauddetection_1149275_1119966_1147294

Online Fraud Detection
This project uses data analysis to identify fraudulent transactions from an online payment dataset.

Project Overview
The goal is to analyze transaction data to detect suspicious activities and potential fraud. The notebook covers data loading, initial exploration, and inspection of the dataset.

Dataset Features
The dataset includes several key columns for analysis:
step: Unit of time (1 step = 1 hour).
type: Transaction method (PAYMENT, TRANSFER, CASH_OUT, DEBIT, CASH_IN).
amount: The value of the transaction.
oldbalanceOrg / newbalanceOrig: Balance before and after the transaction for the sender.
oldbalanceDest / newbalanceDest: Balance before and after the transaction for the recipient.
isFraud: Indicator if the transaction is confirmed as fraud (1) or not (0).

Quick Start
Requirements: Ensure you have pandas and numpy installed.
Data: Place the onlinefraud.csv file in the same directory as the notebook.
Run: Execute the cells in the notebook to view the data structure and initial analysis.

Technologies
Language: Python 3
Libraries: Pandas, NumPy
