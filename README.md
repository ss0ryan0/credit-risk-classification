# credit-risk-classification
Module 20 Supervised Machine Learning
The Purpose of this model is to test and predict the status of the various loans, predicting if they are healthy or are at high risk. This is to ensure lendees, the company's clients, maximum security with their loans while at the same time automating the process to save money for the company instead of hiring more employees to "manually" check the loan status for them.
# Using the Testing Feature Data, The Results are as follows below:
* Accuracy Score: 93.6%
* Healthy Loan Scores:
  * Precision: 100%
  * Recall: 100%
  * F1-score: 100%
  * Support: 18759
* High-Risk Loan Scores
  * Precision: 87%
  * Recall: 89%
  * F1-score: 88%
  * Support: 625
* Accuracy
  * F1-score: 99%
  * Support: 19384
* Macro Average:
  * Precision: 94%
  * Recall: 94%
  * F1-Score: 94%
  * Support: 19384
* Weighted Average:
  * Precision: 99%
  * Recall: 99%
  * F1-Score: 99%
  * Support: 19384
# Using the Resampled Training Data, the results are as follows:
* Healthy Loan Scores:
  * Precision: 100%
  * Recall: 100%
  * F1-score: 100%
  * Support: 18759
* High-Risk Loan Scores
  * Precision: 87%
  * Recall: 100%
  * F1-score: 93%
  * Support: 625
* Accuracy
  * F1-score: 100%
  * Support: 19384
* Macro Average:
  * Precision: 94%
  * Recall: 100%
  * F1-Score: 96%
  * Support: 19384
* Weighted Average:
  * Precision: 100%
  * Recall: 100%
  * F1-Score: 100%
  * Support: 19384

As one can see, when fit with the resampled training data, the accuracy of the F1-score jumps to 100%, as well as the recall. And thus, I recommend this model to the company, as it, for the most part, can accurately predict the recall and F1-score across the board. However, it is imperative for the company to notify clients with high-risk loans of the lower presicion score of below 90% so that said clients can take a loan responsibly. 
