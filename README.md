<h1>Credit Card Fraud Detection</h1>
<h2>Project Overview</h2>

This project focuses on predicting credit card fraud based on a dataset sourced from Kaggle. The model aims to detect fraudulent transactions using machine learning algorithms. Credit card fraud occurs when criminals illegally access and use credit card information, which can happen through various means such as card theft, mail diversion, or unauthorized access to card details.
<h2>Problem Statement</h2>

Credit card fraud detection is a critical challenge faced by financial institutions, as fraudsters continuously evolve their tactics. Identifying fraudulent transactions is essential to protect customers and businesses. In this project, we aim to build a model that can accurately predict whether a transaction is fraudulent or not.
<h2>Dataset</h2>

The dataset used in this project is publicly available on Kaggle. It contains anonymized data of credit card transactions, including features such as:

* Transaction amount
* Time of transaction
* Anonymized variables (due to confidentiality)
* Target variable: 0 for non-fraudulent transactions, 1 for fraudulent transactions

Link to the dataset: <a href = "https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud">Kaggle Credit Card Fraud Detection Dataset</a><br>
<h2>Project Workflow</h2>

<h3>Exploratory Data Analysis (EDA)</h3>

* Understanding the distribution of fraud vs. non-fraud transactions
* Feature importance analysis
* Checking for missing values

<h3>Data Preprocessing</h3>

* Handling missing values
* Feature scaling using RobustScaler
* Balancing the dataset using SMOTE

<h3>Model Selection</h3>

* Random Forest
            
<h3>Model Evaluation</h3>
Metrics used for evaluating the models:

* Accuracy
* Precision
* Recall
* F1-score

<h2>Requirements</h2>

    Python 3.7+
    NumPy
    Pandas
    Scikit-learn
    Matplotlib
    Seaborn
    Jupyter Notebook (for interactive exploration)

<h2>Usage</h2>

Once the model is trained, it can be used to predict whether a new transaction is fraudulent by feeding in the necessary features. Example code to predict on new data:

<h2>Results</h2>

The model achieved a Precision of 89%, Recall of 83%, and F1 score of 86%. The results indicate that the model is capable of detecting fraudulent transactions with a high degree of accuracy while minimizing false positives.
<hr>
<b>Disclaimer:</b> The data used in this project is anonymized and for educational purposes only. It is important to ensure compliance with data privacy regulations when working with real-world financial data.
