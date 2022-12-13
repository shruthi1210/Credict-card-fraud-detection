# Credict-card-fraud-detection
In the financial sector nowadays, credit card fraud is a huge threat. Due of the volume and complexity of the data, manual fraud analysis is not practical. However, one may anticipate that it is possible to do using machine learning if the features are sufficiently illuminating. The project will examine this theory.

Data Description

It only has numeric input variables that have undergone PCA transformation. Unfortunately, we are unable to offer the original characteristics and additional context for the data due to confidentiality concerns. The major components obtained with PCA are features V1, V2,..., V28. The only features that have not been changed with PCA are "Time" and "Amount." The seconds that passed between each transaction and the dataset's first transaction are listed in the feature "Time." The transaction amount is represented by the feature "Amount," which can be utilised for example-dependent, cost-sensitive learning. The response variable, feature "Class," has a value of 1 in cases of fraud and 0 in all other cases.

In this project, the challenge of locating fraudulent transactions using a collection of anonymized attributes was investigated. It has been demonstrated that even a very basic logistic regression model may produce good recall, and that, in terms of AUC, a far more sophisticated Random Forest model outperforms logistic regression. The XGBoost model, however, outperforms both models.
