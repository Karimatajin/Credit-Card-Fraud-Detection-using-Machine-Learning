# Credit-Card-Fraud-Detection-using-Machine-Learning-Python

Credit Card Fraud Detection

# Dataset

The datasets contains credit card transactions over a two day collection period in September 2013 by European cardholders. There are a total of 284,807 transactions, of which 492 (0.172%) are fraudulent.

The dataset contains numerical variables that are the result of a principal components analysis (PCA) transformation. This transformation was applied by the original authors to maintain confidentiality of sensitive information. Additionally the dataset contains Time and Amount, which were not transformed by PCA. The Time variable contains the seconds elapsed between each transaction and the first transaction in the dataset. The Amount variable is the transaction amount, this feature can be used for example-dependant cost-senstive learning. The Class variable is the response variable and indicates whether the transaction was fraudulant.

The dataset was collected and analysed during a research collaboration of Worldline and the Machine Learning Group of Université Libre de Bruxelles (ULB) on big data mining and fraud detection.

# Background

The credit card fraud detection is a process of data investigation made by a data scientist. With predicting a higher accuracy, it will provide the best results in preventing fraudulent transactions. This is achieved through bringing all meaningful features of checking essential conditions of a credit card (e.g. PIN, identity, and balance). Then, running the information through a trained model to predict the accuracy so that it can be classified by whether a transaction is fraudulent or normal. Overall, it’s good to keep in mind that when a cardholder purchases with their card, the information is scrambled by an algorithm. The intent is to make it impossible to access that information without the same encryption key that lets the banks process their transactions. For example, the magnetic stripe on the back of a card is one of the encrypted keys that can only be read by a card scanner. Until the information is decrypted by the key, it’s impossible to use it by a fraudsters. Below is a diagram that represents the process of credit card fraud detection:

![first diagram](https://user-images.githubusercontent.com/43942029/88439642-c3839800-cdd9-11ea-86b1-1fcb8f52fa95.png)
