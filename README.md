# Credit Card Fraud Detection

## Utilizing Machine Learning Models to Detect Credit Card Fraud in an Imbalanced Dataset

Credit card fraud poses a significant challenge for banks and financial institutions, as fraudsters continuously devise new methods to steal credit card information and carry out unauthorized transactions. This project focuses on exploring a dataset of credit card transactions and constructing models to predict and identify fraudulent transactions.

The dataset employed in this project is the Credit Card Fraud Detection dataset from Kaggle, which comprises credit card transactions made by European cardholders. It consists of 284,807 transactions, among which 492 are fraudulent. To protect confidentiality, the dataset includes only numerical input variables resulting from Principal Component Analysis (PCA) transformations. The features encompass 'Time', 'Amount', 'V1' to 'V28', and the target variable 'Class,' indicating whether the transaction is fraudulent (1) or not (0).

The project commences with exploratory data analysis (EDA) to gain insights into the dataset. Subsequently, data processing and modeling are performed. Multiple classification models are built to predict fraudulent transactions, while addressing the challenge of imbalanced classes through undersampling. The models' performance is evaluated using various metrics, including precision, recall, F1-score, and accuracy, to determine the most effective model.

The dataset is split into three portions: 60% for training, 20% for validation, and 20% for testing. Random Undersampling is applied to balance the imbalanced dataset, equalizing the number of fraudulent transactions. The models employed in this project include Logistic Regression, Naive Bayes, Random Forest, and the Dummy Classifier, which serves as a benchmark to assess the performance of the other models.

- Logistic Regression is chosen due to its interpretability and suitability for handling large datasets.
- Naive Bayes is selected for its ability to handle datasets with numerous features and provide fast predictions.
- Random Forest is preferred for its capability to handle complex datasets and mitigate the risk of overfitting.
