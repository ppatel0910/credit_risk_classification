## Background
#### Credit risk poses a classification problem that’s inherently imbalanced. This is because healthy loans easily outnumber risky loans. In this homework, you’ll use various techniques to train and evaluate models with imbalanced classes. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.
#### Using your knowledge of the imbalanced-learn library, you’ll use a logistic regression model to compare two versions of the dataset. First, you’ll use the original dataset. Second, you’ll resample the data by using the RandomOverSampler module from the imbalanced-learn library.
#### For both cases, you’ll get the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.
---
## Credit Risk Analysis Report
### Overview 
#### The purpose of this analysis is to build a logistic regression model that can accurately identify the credit worthiness of an individual using a number of metrics. These metrics include the size of the loan, the income of the borrower, and the debt to income ratio to name a few. The initial logistic regression model created utilized the original imbalanced dataset, and the next model used resampled data. 
---
### Results
#### Model 1
#### - Precision: 99%    Recall: 99%

#### Model 2
#### Precision: 100%    Recall: 99%

---
### Summary
#### The logistic regression model predicts healthy and high-risk loans fairly well. The model appears to correctly make predictions with 99% accuracy.
#### With the resampled data, the logistic regression model is more accurate in overall precision. But in regards to the precision of high-rish loans, the accuracy is lower than with the model using the imbalanced data by 1%. 
