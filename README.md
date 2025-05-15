# Anomaly Detection in Financial Transactions

This project focuses on detecting fraudulent financial transactions using both traditional machine learning techniques and deep learning (Autoencoder) approaches. It is part of a university dissertation aiming to improve the reliability and adaptability of fraud detection systems.


## Project Overview

With the exponential growth of digital transactions, fraud detection has become increasingly critical. Traditional rule-based methods are often rigid and ineffective against evolving fraud patterns. This project explores how deep learning, particularly Autoencoders, can detect anomalies in financial datasets by learning the normal behaviour and flagging deviations.


## Models Used

The notebook evaluates the performance of the following models:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbours (KNN)
- Deep Autoencoder (Unsupervised Anomaly Detection)


## Files Included

- `Anamoly-Detection-Dissertation-System.ipynb`: The main notebook contains the code for data loading, exploration, modelling, and evaluation.
- `README.md`: This documentation file.


## Features Covered

- Data preprocessing and exploration
- Handling class imbalance
- Exploratory Data Analysis (EDA) with visualisations
- Implementation of various ML models for fraud detection
- Unsupervised anomaly detection using deep autoencoder
- Evaluation with metrics like accuracy, precision, recall, F1-score, and confusion matrix


## Dataset Used

**Note**: The datasets used in this notebook are **not included** in this repository due to size constraints.

You can download them from Kaggle:

1. [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
2. [Credit Card Fraud Detection: Trends and Tactics](https://www.kaggle.com/datasets/richardlatimer/credit-card-fraud-detection-trends-and-tactics)

After downloading, please place them in the appropriate path expected by the notebook or modify the file paths accordingly.



## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/ksingh0307/Anomaly-Detection-System.git
   cd Anomaly-Detection-System
