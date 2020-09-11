# Credit-Card-Fraud-Detection

### Description :- 
    The objective is to build fraud prevention system for credit card transaction with higher accuracy of fraud detection by decreasing the amount of false positives

---

### Goal :-
    To achieve higher accuracy of fraud detection by decreasing the amount of false positives.

---

### Data Details :-

    The data is broken into two files identity and transaction , which are joined by TransactionID .
      - Categorical Features - Transaction Table
          ProductCD , card1 - card6 , addr1 , addr2 , P_emaildomain , R_emaildomain , M1 - M9.
      - Categorical Features - Identity Table
          DeviceType , DeviceInfo , id_12 - id_38.
          
          (Data set : https://www.kaggle.com/c/ieee-fraud-detection/data)
          
---

### Methods, Algorithms, Tools :-

    - Merged the two datasets.
    - Filled null datasets.
    - Used one hot coding to convert the categorical features into numerical features.
    - Used K-nearest neighbor (KNN) algorithm to develop a prediction model.
    - Used Decision Tree algorithm to develop a prediction model.
    - Used Logistic Regression Classifier to develop a prediction model.
    - Used the ROC curve to show the AUC.
    
### Final Result :-
      
      The Logistic Regression gives the best accuracy (0.965806719273885) of all algorithms, hence we conclude that Logistic Regression is the best approach for our problem.
