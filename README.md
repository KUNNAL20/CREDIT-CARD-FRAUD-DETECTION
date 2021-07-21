# CREDIT-CARD-FRAUD-DETECTION

Handle the imbalanced data and predict whether the transaction is fraudulent or Legit

Kaggle Link: https://www.kaggle.com/mlg-ulb/creditcardfraud


In this project we will predict fraudulent credit card transactions with the help of Machine learning models.

In order to complete the project, we are going to follow below high level steps to build and select best model.

Read the dataset and perform exploratory data analysis
Building different classification models on the unbalanced data
Building different models on 2 different balancing technique.
Random Undersampling
SMOTE

## What is Credit Card Fraud?
Credit card fraud is when someone uses another person's credit card or account information to make unauthorized purchases or access funds through cash advances. Credit card fraud doesn’t just happen online; it happens in brick-and-mortar stores, too. As a business owner, you can avoid serious headaches – and unwanted publicity – by recognizing potentially fraudulent use of credit cards in your payment environment.

## Business Problem Overview
For many banks, retaining high profitable customers is the number one business goal. Banking fraud, however, poses a significant threat to this goal for different banks. In terms of substantial financial losses, trust and credibility, this is a concerning issue to both banks and customers alike.

It has been estimated by Nilson report that by 2020 the banking frauds would account to $30 billion worldwide. With the rise in digital payment channels, the number of fraudulent transactions is also increasing with new and different ways.

In the banking industry, credit card fraud detection using machine learning is not just a trend but a necessity for them to put proactive monitoring and fraud prevention mechanisms in place. Machine learning is helping these institutions to reduce time-consuming manual reviews, costly chargebacks and fees, and denials of legitimate transactions.

## Algorithms
I have used three classification algorithms namely Logistic Regression CV, Random Forest Classifier and XGBoost Classifier. I have trained the classifier using the original dataset, dataset after implying UnderSampling and a dataset obtained after performing Synthetic Minority Over-Sampling Technique (SMOTE) on the original dataset. I have split the data into training and test set at a ratio of 70:30.

## Metrics Used to Evaluate Classifier Performance
I have used F1 Score, Recall, Precision, Confusion Matrix and Average ROC_AUC score as metrics to evaluate the classifiers as they give a better indication of the model compared to accuracy.

## Results
The XgBoost gives the best Recall score on the original dataset among the three algorithms. However, it lags the other two classifiers on all other metrics. Random Forest gives the best Recall and F1 score among the classifiers when impling with undersampling. Using the classifiers on the SMOTE dataset improves the Recall, Precision, F1 Score of the models 
