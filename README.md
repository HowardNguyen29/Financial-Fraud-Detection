# Financial-Fraud-Detection

## Overview:
This project aims to build a machine learning model to detect fraud in transaction data. The model is designed to classify transactions as fraud or non-fraud based on several features like transaction amount, customer demographics, and merchant information. We use both supervised and unsupervised learning techniques to tackle the imbalance between fraud and non-fraud cases in the dataset.

## Key Features
Fraud Detection: Classifying transactions into fraud or non-fraud categories.
Anomaly Detection: Identifying anomalies in transaction patterns using unsupervised learning techniques.
Data Analysis & Visualization: Data preprocessing, feature selection, and visualization using various plotting libraries.
Handling Imbalanced Data: Special handling of highly imbalanced data between fraud and non-fraud cases.

## Technologies Used
Python: Programming language used for data manipulation, analysis, and modeling.
Pandas: Data processing and analysis.
Scikit-learn: Machine learning library used for model building, training, and evaluation.
Seaborn/Matplotlib: For data visualization and plotting heatmaps, histograms, and other plots.
Jupyter Notebooks: For interactive data analysis and model building.
Tensorflow: For creating neuron networks.

## Data
The dataset consists of transactional data with features such as amt, city_pop, distance, age, fraud_merchant_pct, and job_encoded.
The target variable is whether a transaction is fraudulent (fraud).
The data is imbalanced, with a much higher number of non-fraud transactions than fraud ones.
Data link: https://www.kaggle.com/datasets/kartik2112/fraud-detection/

## Model Performance
Overall Accuracy: The model achieves ~90% accuracy on the whole dataset, with performance similar on both the training and test sets.
Fraud Detection: The accuracy for fraud cases is ~60% on the training set and ~59% on the test set, indicating relatively consistent performance across both sets.
