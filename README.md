Credit Card Fraud Detection

Project Overview
This project focuses on the detection of fraudulent transactions using credit card data. We employ machine learning models such as Random Forest and Autoencoders to identify fraudulent activities, aiming to help prevent financial losses for cardholders. This repository contains all the necessary code and models used for the analysis.

Dataset Description
The dataset consists of transactions made by European cardholders in September 2013. It is highly unbalanced, containing 492 frauds out of 284,807 transactions, which accounts for only 0.172% of all transactions.

Features
Time: Seconds elapsed between each transaction and the first transaction in the dataset.
Amount: Transaction amount; this feature can be used for cost-sensitive learning.
V1 to V28: Anonymous features generated through a PCA transformation to protect user identities.
Class: The response variable where 1 indicates fraud and 0 indicates a legitimate transaction.

Models Used
Random Forest
Overview: Employs an ensemble of decision trees to improve predictive accuracy and control over-fitting.
Purpose: Effectively handles the unbalanced nature of the dataset and provides feature importance scores.
#Autoencoder
Overview: A type of neural network that learns to encode the unlabeled data efficiently.
Purpose: Identifies outliers in transaction data, which are potential frauds, by learning to reconstruct the input data.

Results and Visualization
Included in the repository are notebooks that outline the modeling process, feature importance analysis, and the results obtained from the models. Visualizations such as ROC curves, precision-recall curves, and feature importance plots are used to effectively interpret the models' performance.
