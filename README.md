# Credit Risk Analysis Report

1.	An overview of the analysis: Explain the purpose of this analysis.
The purpose of the analysis is to use historic lending data to predict future loan risk.  Loan risk from a lending services company was analyzed to determine the creditworthiness of borrowers using the loan status data to predict future outcomes.

2.	The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.

•	Accuracy score – As the accuracy score of the model is the proportion of correct predictions over total predictions, looking at the classification report, the model's accuracy is a good indication predicting if a loan has a high risk of default because of the high accuracy. Based on my analysis, the balanced accuracy score is about 94% while accuracy score on the classification report is about 99%.

•	Precision score – As Precision score measures how good the model is when the prediction is positive, the Precision score of about 87% for high risk loan can be trusted in this model. This can be a good indication of how well the model is likely to perform in real life.

•	Recall score – As Recall measures how good our model is at correctly predicting positive classes, the Recall score of 89% for high risk loan seems to be strong prediction. This can be a good indication of how well the model is likely to perform in real life.



3.	A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.

Looking at the overall classification report, the logistic regression seems to be predicting the high-risk loan well with an accuracy of a 100%, a precision of 87%, recall of 89% and f-1 of 88%. A strong precision and recall on the test dataset is a good indication about how well the model is likely to perform.
However, a precision, recall and f1-score of 100% for the healthy loans seem kind of suspicious in the sense that, does it really mean the model is perfectly predicting healthy loans? I would not recommend this model to predict healthy loans based on the 100% score for precision, recall and f-1 unless there is another indication (such as creating another predictive model other than a logistic regression) that supports the conclusion that the model is 100%(perfectly) predicting healthy loans.

