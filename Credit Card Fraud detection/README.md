# Fraud detection using credit cards transaction dataset

The Institute of International Finance and Deloitte LLP highlights that: There is growing consensus that the current global framework for fighting financial crime is not as effective as it could be and that more needs to be done at the international, regional and national levels to help identify and stem the flow of illicit finance – an activity which supports some of the worst problems confronting society today, including terrorism, sexual exploitation, modern slavery, wildlife poaching and drug smuggling.

Credit card fraud is one of such crimes. Credit card fraud is a form of identity theft that involves an unauthorized taking of another’s credit card information for the purpose of charging purchases to the account or removing funds from it.Global economy pays the price of more than $ 24 billion per year due to these frauds.

Whilst these problems in themselves are pressing and need a multifacted approach for resolution, financial institutions are facing even greater pressure to modernize and make more robust their AML functions for various risk management objectives.

In this project, we'll use ML to predict whether a credit card transaction is Fraudulent or genuine based on various transaction details in an attempt to curb this.

## Requirements

-Python
-NumPy
-Pandas
-Matplotlib
-Scikit-learn

## Model Evaluation

- **Recall:** This is the measure of our model correctly identifying True Positives, in this case for all Fraudulent transactions, how many we correctly identified as fraudulent transactions. It takes into account False Negatives ie Fraudulent cases that the model mis-classified.

- **Precision:** This is the ratio between the True Positives and all the Positives, in this case the measure of transactions we classify as Fraud out of all the fraudulent transactions.

- **F1 score:** F1 score is the harmonic mean of precision and recall. It takes into account both false positives and false negatives. A high F1 score indicates better performance of the model.

Important to note is that the model could be tweaked to focus more on either precision or recall given the desired effect or application
