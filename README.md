# detecting_credit_card_fraud
## Using Logistic Regression, SVM, Naive Bayes and Random Forest to detect credit card fraud in an imbalanced dataset.

Credit card fraud is a major concern for banks and financial institutions. Fraudsters use various techniques to steal credit card information and make unauthorized transactions. In this project, we will explore a dataset containing credit card transactions and build models to predict fraudulent transactions.

We will use the Kaggle dataset Credit Card Fraud Detection which contains credit card transactions made by European cardholders. The dataset consists of 284,807 transactions, out of which 492 are fraudulent. The data contains only numerical input variables which are a result of Principal Component Analysis (PCA) transformations due to confidentiality issues. The features include 'Time', 'Amount', and 'V1' through 'V28', as well as the 'Class' variable, which is the target variable indicating whether the transaction is fraudulent (1) or not (0).

In this project, we start with exploratory data analysis (EDA) to get a better understanding of the data. Next, we perform data processing and modeling, where we build several classification models to predict fraudulent transactions. We also address the issue of imbalanced classes by using undersampling. Finally, we evaluate the performance of the models and choose the best one based on various evaluation metrics such as precision, recall, F1-score, and accuracy.

#### The dataset is divided into 60% for training, 20% for validation, and 20% for testing. To balance the imbalanced dataset, Random Undersampling was used to match the number of fraudulent transactions. Logistic Regression and Random Forest models were used, and good results were produced.

    - Logistic Regression is widely used for fraud detection because of its interpretability and ability to handle large datasets.
    - Naive Bayes is commonly used for fraud detection because it can handle datasets with a large number of features and can provide fast predictions.
    - Random Forest is commonly used for fraud detection because it can handle complex datasets and is less prone to overfitting.
    - The Dummy Classifier is a simple algorithm used as a benchmark to compare theperformance of other models.
