### Problem Statement:

Electronic fraudulent issue is gaining more and more attention nowadays due to an increasing popularity in digital and online purchases. It is important that financial institutions including banking and credit unions, are able to recognize or be aware of potential fraudulent electronic transactions early in time so that customers are not charged for items that they did not purchase and the financial institutions do not suffer financial loss or further threat from fraudulent activities.


In this project, data cleaning, exploratory data analysis, feature engineering have been performed to modify the datasets (over 6 million transactions). Potential statistical correlations between different features and fraud transaction occurence have been assessed and and the distribution patterns and trends of each feature have been explored. Five different machine learning algorithms have been tested on the newly created features for detecting fraudulent transactions.

### Approach:

EDA, Data cleaning, Feature Engineering and Machine Learning (LogisticRegressionCV, Gradient Boosting Classifier, Random Forest Classifier, Decision Tree and K Neighbors Classifier) to predict fraudulent transactions.

### Conclusions:

Feature engineering greatly improved ML performances: random forest model gives close to 100% prediction accuracy, with ROC score close to 1, 100% ture negative rate, 0 false positive rate, 0.5% false negative rate and 99.5% true positive rate.

### Code:
https://nbviewer.jupyter.org/github/huanxia1/Identifying-Fraudulent-Electronic-Transactions/blob/master/Detection_of_fraud_electronic_transactions.ipynb
