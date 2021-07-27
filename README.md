# Credit-Card-Fraud
## Credit Card Fraud Detection using Machine Learning

  It is vital that credit card companies are able to identify fraudulent credit card transactions so that customers are not charged for items that they did not purchase. Such problems can be tackled with Data Science and its importance, along with Machine Learning, cannot be overstated. This project intends to illustrate the modelling of a data set using Machine Learning algorithms for Credit Card Fraud Detection. The Credit Card Fraud Detection Problem includes modelling past credit card transactions with the data of the ones that turned out to be fraud. The best model can then be used in future to recognize whether a new transaction is fraudulent or not. Our objective here is to detect 100% of the fraudulent transactions while minimizing the incorrect fraud classifications. Credit Card Fraud Detection is a typical sample of classification problems.

  The Credit Card Fraud Detection dataset used here contains a total of 2,84,808 credit card transactions of a European bank data set. It was obtained from ‘kaggle.com’, a data  analysis website which provides datasets. The dataset consists of 31 columns out of which 28 columns, named as V1 to V28 are only numerical input variables which are the result of  a PCA transformation. The remaining 3 columns represent Time, Amount and Class. Time shows the time gap between the first transaction and the following one. Amount is the amount of money transacted. Class 0 represents a valid transaction and 1 represents a fraudulent one. Since, the ‘time’ column does not contribute to building the model, it was dropped from the dataset after importing.

  In this project, 6 Machine learning algorithms- Logistic regression, Decision Tree Random forest,KNN,SVM,Naive Bayes were implemented on the Credit Card Fraud dataset and their performances were compared.Sensitivity, Specificity, accuracy and error rate are used to evaluate the performance for the proposed system. The accuracy for Logistic regression, Decision Tree, Random forest, KNN, SVM, NaiveBayes are 0.99919, 0.99936, 0.99929, 0.99952, 0.99931, 0.99913 respectively.
  
  Thus, in terms of accuracy, Naive Bayes < Logistic Regression < SVM < Random Forest < Decision Tree < KNN. 
  
  For f1-score, Naive Bayes < Logistic Regression < Random Forest < Decision Tree < KNN.
  
  For AUC-ROC Score, Logistic Regression < Naive Bayes < SVM < Random Forest < Decision Tree < KNN. 
  
  By comparing all the six methods, we found that the KNN classifier is best out of all methods. 
  
  Fraud detection is a complex issue that requires a substantial amount of planning before throwing machine learning algorithms at it. The findings obtained here may not be generalized to the global fraud detection problem. As future work, some effective  algorithm which can perform well for the classification problem with variable misclassification costs could be developed. Having a data set with non-anonymized features would make this particularly interesting as outputting the feature importance would enable one to see what specific factors are most important for detecting fraudulent transactions.
  
  ### The dataset used for this project can be downloaded from the following url:
  https://www.kaggle.com/mlg-ulb/creditcardfraud
