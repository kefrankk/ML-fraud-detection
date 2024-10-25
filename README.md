# Fraud detection using Isolation Forest

This project uses **Isolation Forest** to detect potential fraud in transactional data.  I used the **Credit Card Fraud Detection** dataset available on Kaggle, which contains 294,588 credit card transactions. Given that the dataset is unlabeled, the Isolation Forest algorithm helps in identifying anomalies (fraudulent transactions) based on an estimated contamination rate, representing the expected proportion of fraud cases.


## Project Overview
This project aims to detect suspicious transactions by leveraging the Isolation Forest model, widely used for anomaly detection in financial data. The model identifies anomalies by isolating data points that differ significantly from the majority, making it suitable for fraud detection in the absence of labeled data.


### Key Steps

1. Data Preprocessing:

    - Handle categorical data with **One-Hot Encoding** to ensure all features are numeric.
    - Normalize numerical features to improve the efficiency and accuracy of the model.

2. Model Training:

    - **Isolation Forest** is trained with an estimated contamination level based on typical fraud rates in similar datasets.


### Key Files
`data/`: Contains sample data for training and testing.

`fraud_detection_model.ipynb`: Jupyter notebook detailing data exploration, preprocessing, and model training.



## Installation

1. Clone the repository:

```
git clone https://github.com/yourusername/fraud-detection
cd fraud-detection
```

2. Install dependencies:

```
pip install -r requirements.txt
```
