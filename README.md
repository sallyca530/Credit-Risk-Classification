## Credit Risk Classification - Supervised Machine Learning

### Overview
This project delves into the intricate task of gauging the creditworthiness of loan applicants using the logistic regression model. The analysis revolves around crucial factors such as loan size, interest rate, borrower income, debt-to-income ratio, number of credit accounts, derogatory marks, total debt, and loan status.

### Tools used in Machine Learning
* Python
* Pandas
* Pathlib
* sklearn.metrics

### Data Analysis
The initial phase encompassed segregating data into target variables, followed by a train-test split. The logistic regression model was applied to the training subset, culminating in precise predictions. The evaluation was conducted using the accuracy score, confusion matrix, and a classification report.

### Results
* Accuracy score: 99%

Healthy loans:
1. Precision: 100%
2. Recall: 99%
3. F1-Score: 100%

High-risk loans:
1. Precision: 85%
2. Recall: 91%
3. F1-score: 88%

### Summary
The logistic regression model showcased outstanding prowess in evaluating healthy loans, achieving a high degree of precision, recall, and F1-score. Though the performance dipped slightly for high-risk loans, the model exhibited credible precision, recall, and F1-score. With an accuracy score of 99%, this model is highly dependable for inspecting the creditworthiness of both healthy and high-risk loans. The heightened recall for high-risk loans underscores its significance in making informed decisions and prioritizing loan approval for creditworthy applicants.