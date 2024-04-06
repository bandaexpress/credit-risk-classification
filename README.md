# credit-risk-classification
Module 20 assignment from Columbia University Data Analytics Bootcamp

## Overview
This repository uses various techniques to train and evaluate a model based on loan risk that can identify the creditworthiness of borrowers.

### Data
Historical lending activity from a peer-to-peer lending services company

### Results
![image](https://github.com/bandaexpress/credit-risk-classification/assets/17518802/40d3cc09-9554-4e7e-8add-7864ebd8314d)


#### Precision
- For label 0 (healthy loan), the precision is 1.00, indicating that almost all the predicted healthy loans were actually healthy. 
- For label 1 (high-risk loan), the precision is 0.85, which means about 85% of the predicted high-risk loans were correctly classified.

#### Recall
- For label 0, the recall is 0.99, indicating that almost all the actual healthy loans were identified as such. 
- For label 1, the recall is 0.91, meaning that around 91% of the actual high-risk loans were correctly identified.

#### F1-score
- The F1-score for label 0 is 1.00, indicating excellent balance between precision and recall.
- For label 1, the F1-score is 0.88, which suggests a slightly lower balance between precision and recall compared to label 0.

#### Accuracy
- The accuracy of the logistic regression model is 0.99, which means it correctly predicted about 99% of the loans in the dataset.

#### Macro Avg
- The macro-average precision is 0.92, recall is 0.95, and F1-score is 0.94.

#### Weighted Avg
- The weighted average precision, recall, and F1-score are all close to 0.99, reflecting the model's high accuracy due to the large number of healthy loans compared to high-risk loans.

### Summary
Overall, the logistic regression model shows excellent performance in predicting healthy loans (label 0), with very high precision, recall, and F1-score. 

The logistic regression model works well to predict the '0' (healthy loan) label with a precision of 1.00, which indicates that almost all the predicted healthy loans were actually healthy. For the '1' (high-risk loan) label, the precision is 0.85 which means that 85% of the predicted high-risk loans were correctly classified. The accuracy score of .99 means that the model correctly predicted about 99% of the loans in the dataset.

For high-risk loans (label 1), while the performance is slightly lower compared to label 0, it still demonstrates good predictive capabilities with acceptable precision, recall, and F1-score values. The recommendation would be to use the high-accuracy performing model.
