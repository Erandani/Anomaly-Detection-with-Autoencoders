# Anomaly-Detection-with-Autoencoders:Detecting Credit Card Fraud 

The dataset we are going to use is the “Credit Card Fraud Detection” dataset and can be found in Kaggle.

The dataset contains 284,807 credit card transactions from european cardholders. For security reasons the original features of the dataset are not available. Instead, 28 features that are the result of PCA of original features are available. There is also, the amount of each transaction and a “Time” column. The last one counts the number of seconds between each transaction and the first transaction in the set. Finally, the type of each transaction is in column “Class”. Fraudulent transactions are represented with 1 and non-fraudulent with 0.

 Our objective is to find a way to distinguish frauds from the genuine transactions without using labels given,  as a form of unsupervised learning problem.
