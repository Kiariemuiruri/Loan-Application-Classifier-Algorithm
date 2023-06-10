# Loan-Application-Classifier-Algorithm
ML Classification Algorithm to predict Approval or Decline of a Loan. 
The model predicts whether a customer loan application is approved or not based on information they provide.
### Feature Engineering (Dimentionality Reduction)
* Some of the features might be redundant in explaining the variations of the Loan_Status, and after PCA, only six features are found to be explaining 80% of the total variations.
* There is Polynomial features for interactions only to capture any missing information from the input features
![PCA](https://github.com/Kiariemuiruri/Loan-Application-Classifier-Algorithm/blob/main/PCA.png)
* The six features are the one considered in training the algorithm.
### Selecting the Model
* Given the positive value for the Loan_Status is 1 (loan approved), <b>Logostic regression</b> records a higher precision than other algorithmns, i.e, <b> Fewer loans will be approved while actually they should be declined</b>
* It has hte lowest False Negative (FN) value.
![report](https://github.com/Kiariemuiruri/Loan-Application-Classifier-Algorithm/blob/main/download.png)<br>
#### The model is finally Pickled in a file ready for Deployment
