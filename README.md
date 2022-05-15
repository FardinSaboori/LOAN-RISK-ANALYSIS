# LOAN-RISK-ANALYSIS
## In this project i used the publicly available dataset provided by lending club to analyze the trends and correlation of the variables in the dataset to the label that is called "Loan_statues", we will then make predictions to identify "Fully Paid" and "Charged Off" loans.
* Two models were trained for this purpose, XGBClassifier and a NN to compare the results through a confusion matrix and AUC.
* Depending on the business value and the expectations of the model we can play around with the probability threshhold in the NN model.
* To find the business value, we can consider the following, correctly found bad loans as the loss avoided and incorrectly labeled bad loans as profit forfeited.
* Business Value = (loss avoided - profit forfeited)
