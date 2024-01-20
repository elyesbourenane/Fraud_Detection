# Fraud Detection App

This Jupyter notebook contains a fraud detection application using a dataset with transaction information. The goal is to predict whether a transaction is fraudulent or not based on various features.


## Dataset
You can download the dataset (csv file) here: https://zenodo.org/records/10539918?token=eyJhbGciOiJIUzUxMiJ9.eyJpZCI6Ijg5NzQ4MzEwLWUwMjAtNGI4Zi04MTRhLWZkNTdkNDdkYTc2OSIsImRhdGEiOnt9LCJyYW5kb20iOiI1ZGFhN2E2ZTM5MmIxODM3NDYxMDVmNTNiYWRiNGYwYyJ9.gXBQ8exgyPvzBMJ_qQdnEeW_AhR9pApcAvRHTiSkn6CluvTKBpNo2H6QnIisWXLzdzxxiEpb-QIclvxaPZGNTw
<br>

The dataset includes the following columns:

- `step`: The step in the transaction, a unit of time.
- `type`: The type of transaction (e.g., PAYMENT, TRANSFER, CASH_OUT).
- `amount`: The amount of the transaction.
- `nameOrig`: The name of the origin account.
- `oldbalanceOrg`: The old balance of the origin account before the transaction.
- `newbalanceOrig`: The new balance of the origin account after the transaction.
- `nameDest`: The name of the destination account.
- `oldbalanceDest`: The old balance of the destination account before the transaction.
- `newbalanceDest`: The new balance of the destination account after the transaction.
- `isFraud`: Binary indicator of whether the transaction is fraudulent (1) or not (0).
- `isFlaggedFraud`: Binary indicator if the transaction is flagged as fraudulent (1) or not (0).

## Exploratory Data Analysis

The notebook performs exploratory data analysis (EDA) on the dataset, including summary statistics, data types, and visualizations to understand the characteristics of the data.

## Data Preprocessing

Data preprocessing steps are taken to handle missing values, convert categorical variables into numerical format, and scale numerical features.

## Model Training

A neural network model is trained using Keras for fraud detection. The model is evaluated on the validation set, and accuracy and loss metrics are displayed.

## Model Evaluation

The trained model is evaluated on the test set, and metrics such as loss and accuracy are presented.
