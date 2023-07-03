# Credit_card_Fraud_Detection_Model
This project aims to predict fraudulent credit card transactions using machine learning models. The detection of fraudulent transactions is crucial from both the bank's and the customer's perspective, as the banks cannot afford to lose their customers' money to fraudsters. Every fraud is a loss to the bank, as they are responsible for the fraudulent transactions.

The dataset used in this project contains transactions made over a period of two days in September 2013 by European credit cardholders. The dataset is highly unbalanced, with the positive class (frauds) accounting for only 0.172% of all transactions. Therefore, handling the data imbalance is a crucial aspect of building the models.

The project involves the following steps:

Data Exploration: The dataset is explored to understand its structure, check for missing values, and analyze the distribution of classes.

Data Preprocessing: The dataset is preprocessed by dropping irrelevant columns, scaling the numeric features, and mitigating skewness in the data.

Model Building: Several machine learning algorithms are applied to build models for fraud detection. The models include Logistic Regression, Decision Tree, Random Forest, and Support Vector Machines (SVM).

Hyperparameter Tuning: The models are tuned using grid search and cross-validation to find the best combination of hyperparameters.

Evaluation: The models are evaluated using performance metrics such as ROC-AUC score, accuracy, sensitivity, specificity, and F1-score. The ROC curves are plotted to visualize the performance of the models.

Model Comparison: The performance of different models is compared to determine the best model for fraud detection in this particular dataset.

This project provides insights into how machine learning models can be used to detect fraudulent credit card transactions and helps banks improve their fraud detection systems to protect their customers' money.

The dataset can be found at : https://www.kaggle.com/mlg-ulb/creditcardfraud
