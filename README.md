# credit-risk-classification
Overview
-
the purpose of this challenge was to use various techniques to train and evaluate a model based on loan risk. things such as income, the number of accounts, debt, and load sizes were used to evaluate the loan status. some of the key points of the machine learning process was establishing an X and Y variable, splitting the dataset into training and testing data and being able to analyize the results.

Results
-
Confusion Matrix:
- True Positive: 18658
- False Positive: 37
- False Negative: 107
- True Negative: 582

Classification Report:
- Precision:
  - Healthy: 1.00
  - High-Risk Loan: 0.84
- Recall:
  - Healthy: 0.99
  - High-Risk Loan: 0.94
- F1-score:
  - Healthy: 1.00
  - High-Risk Loan: 0.89
- Accuracy: 0.99
- Macro Avg:
  - Precision : 0.92
  - Recall : 0.97
  - F1-score : 0.94
- Weighted Avg:
  - Precision : 0.99
  - Recall : 0.99
  - F1-score : 0.99

Summary
-
The model demonstrates excellent performance with an overall accuracy of 99%. The precision and recall scores suggest that the model is highly effective at identifying healthy loans while still maintaining a solid ability to detect high-risk loans. The model’s performance appears well-suited to the problem at hand, where correctly identifying high-risk loans is more important than falsely classifying a healthy loan as high-risk. Therefore, this model is recommended for deployment, with the caveat that ongoing monitoring and possible adjustments should be made to further reduce false negatives without compromising overall performance.
