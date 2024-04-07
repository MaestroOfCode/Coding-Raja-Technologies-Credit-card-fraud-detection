About Dataset
Context:
Effective detection of fraudulent credit card transactions is crucial for credit card companies to safeguard customers from unauthorized charges and maintain financial integrity.

Content:
The dataset comprises transactions conducted by credit cards in September 2013, involving European cardholders. It spans transactions across two days, encompassing 492 frauds out of a total of 284,807 transactions. It's important to note that the dataset exhibits significant class imbalance, with fraudulent transactions constituting only 0.172% of the total transactions.

The dataset primarily consists of numerical input variables resulting from a Principal Component Analysis (PCA) transformation. Unfortunately, due to confidentiality constraints, the original features and additional background information about the data cannot be disclosed. The features V1 through V28 represent the principal components obtained through PCA, while the 'Time' and 'Amount' features remain untransformed. 'Time' denotes the seconds elapsed between each transaction and the first recorded transaction in the dataset, while 'Amount' signifies the transaction amount. Notably, the 'Amount' feature can be particularly useful for example-dependent cost-sensitive learning. Additionally, the 'Class' feature serves as the response variable, taking a value of 1 in the case of fraud and 0 otherwise.
