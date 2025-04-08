# Credit-Card-Fraud-Detection 
![credit-card-fraud-detection](https://github.com/user-attachments/assets/11efaf5f-4dcd-4899-8efe-ce29cdb0890b)

Presentation Link: [Credit Card Fraud Detection.pptx](https://github.com/user-attachments/files/19648962/Credit.Card.Fraud.Detection.pptx)

# Problem statement

The problem statement chosen for this project is to predict fraudulent credit card transactions with the help of machine learning models.
In this project, we will analyse customer-level data which has been collected and analysed during a research collaboration of Worldline and the Machine Learning Group.
The dataset is taken from the Kaggle Website website and it has a total of 2,84,807 transactions, out of which 492 are fraudulent. Since the dataset is highly imbalanced, so it needs to be handled before model building.

# Business Problem Overview

Banking fraud threatens customer trust and causes major financial losses. With digital payments on the rise, fraud is increasing in both volume and complexity. According to the Nilson Report, global banking fraud could reach $30 billion by 2020. Machine learning has become essential for credit card fraud detection, helping banks automate monitoring, reduce manual checks, and prevent fraudulent transactions efficiently.

# Understanding and Defining Fraud

Credit card fraud is any dishonest act and behaviour to obtain information without the proper authorization from the account holder for financial gain. Among different ways of frauds, Skimming is the most common one, which is the way of duplicating of information located on the magnetic strip of the card. Apart from this, the other ways are:
 
  * Manipulation/alteration of genuine cards
  * Creation of counterfeit cards
  * Stolen/lost credit cards
  * Fraudulent telemarketing

# Data Source

The dataset contains credit card transactions made by European cardholders over two days in September 2013. It includes 284,807 transactions, of which only 492 are fraudulent—making the data highly imbalanced, with frauds representing just 0.172% of all transactions.

To ensure confidentiality, the dataset has been transformed using Principal Component Analysis (PCA), except for the features 'Time' and 'Amount'.

  * 'Time' indicates the seconds elapsed since the first transaction.
  * 'Amount' is the transaction amount.
  * 'Class' is the target variable, where 1 denotes fraud and 0 denotes a legitimate transaction.
  *  Features V1 to V28 are the principal components derived from PCA.

Dataset Link: https://www.kaggle.com/mlg-ulb/creditcardfraud

# Algorithm

1. Logistic Regression
2. Random Forest

# Conclusion

In conclusion, the main objective of this project was to find the most suited model for creditcard fraud detection in terms of the machine learning techniques chosen for the project. It was met by building the Two models and finding the accuracies of them all; the best in terms of accuracy is Logistic Regression and Random Forest, which scored 100 on credit card fraud and increased the customer’s satisfaction as it will provide them with a better experience and feeling secure.
