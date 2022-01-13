# Fraud Detection with Machine Learning On Banksim Data
Fraudulent behavior can be seen across many different fields such as e-commerce, healthcare, payment and banking systems. Fraud costs businesses millions of dollars each year.

Automated detection of fraudulent behavior can be done in various ways including rule based approaches and machine learning. This repository uses machine learning approach for classification of fraudulent transactions.
The synthetically generated dataset consists of payments from various customers made in different time periods and with different amounts.

If you want more information on the dataset you can refer below to the Dataset title for the dataset link and information.

This project will be considered successful if our model achieves at least 80% accuracy

To view the Overall results, just check the file called Fraud Detection.ipynb from inside the repo.

For those who do not wish to run the script to acquire the results, here is a quick recap of the classification results of the machine learning models used in the script:

Classification Report for K-Nearest Neighbours (1:fraudulent,0:non-fraudulent) :

class	precision	recall	f1-score	support
0	1.00	1.00	1.00	176233
1	0.83	0.61	0.70	2160
Confusion Matrix of K-Nearest Neigbours:
[175962 271]
[ 845 1315]


Classification Report for XGBoost :

class	precision	recall	f1-score	support
0	1.00	1.00	1.00	176233
1	0.89	0.76	0.82	2160
Confusion Matrix of XGBoost:
[176029 204]
[ 529 1631]


Classification Report for Random Forest Classifier :

class	precision	recall	f1-score	support
0	1.00	0.96	0.98	176233
1	0.24	0.98	0.82	2160
Confusion Matrix of Random Forest Classifier:
[169552 6681]
[ 39 2121]


Classification Report for Ensembled Models(RandomForest+KNN+XGBoost) :

class	precision	recall	f1-score	support
0	1.00	1.00	1.00	176233
1	0.73	0.81	0.77	2160
Confusion Matrix of Ensembled Models:
[175604 629]
[ 417 1743]

# Dataset
https://www.kaggle.com/turkayavci/fraud-detection-on-bank-payments/data

