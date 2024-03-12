Analysis Overview

The aim of this analysis is to predict whether a loan is healthy (0) or high-risk (1) based on historical loan data and borrower information. The loan data includes factors such as loan amount, interest rate, and derogatory marks, while the borrower information consists of income, debt-to-income ratio, number of accounts, and total debt. A Logistic Regression Model is employed to predict the risk level of future loans using these collected measures.

Analysis Results
----------------

It is crucial to acknowledge that the dataset was imbalanced, with 75,036 healthy instances and only 2,500 high-risk instances out of a total of 77,536 instances.

*   Model Accuracy:
    *   The model achieved an impressive 99% accuracy and 95% balanced accuracy.
*   Model Precision:
    *   The model's precision was lowest when predicting high-risk loans, at 85%.
    *   Healthy loans achieved a perfect 100% precision, possibly due to the imbalance in the dataset.
*   Model Recall:
    *   The recall for healthy loans was 99%.
    *   The recall for high-risk loans was 91%.

Analysis Summary
----------------

In summary, the machine learning model demonstrated excellent performance overall.

The number of loans predicted as high-risk but actually categorized as healthy is approximately half the number of actual healthy loans incorrectly predicted as high-risk.

The number of high-risk loans that were missed by the model was only one-tenth of the number of predicted high-risk loans that were actually healthy.

While I recommend using this model as a tool, it is important to consider that the high-risk data may not be as well-represented as necessary to accurately categorize loans as high-risk. Further improvements to the model could be made by collecting more high-risk loan data to balance the dataset and enhance its predictive capabilities.
