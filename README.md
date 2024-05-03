Credit Card Fraud Detection
Project Overview
This project focuses on the detection of fraudulent transactions using credit card data. By employing machine learning models such as Random Forest and Autoencoders, we aim to identify fraudulent activities, helping prevent financial losses for cardholders. This repository contains the code and models used in the analysis.

Dataset Description
The dataset used in this project comprises transactions made by European cardholders in September 2013. This dataset is highly unbalanced with 492 frauds out of 284,807 transactions, making up only 0.172% of all transactions.

Features
Time: Time elapsed between each transaction and the first transaction in the dataset (in seconds).
Amount: Transaction amount; this feature can be used for cost-sensitive learning.
V1 to V28: Anonymous features generated as a result of a PCA transformation to protect user identities.
Class: The response variable where 1 represents fraud and 0 represents a legitimate transaction.

Models Used
Random Forest
Overview: Utilizes an ensemble of decision trees to improve predictive accuracy and control over-fitting.
Purpose: Effectively handles the unbalanced nature of the dataset and provides importance scores for various features.
Autoencoder
Overview: A type of neural network used to learn efficient codings of unlabeled data.
Purpose: Identifies outliers in transaction data, which are potential frauds, by learning to reconstruct the input data.

Results and Visualization
The repository includes notebooks that detail the modeling process, feature importance analysis, and the results of the models used. Visualizations such as ROC curves, precision-recall curves, and feature importance plots are included to interpret the models' performance effectively.
