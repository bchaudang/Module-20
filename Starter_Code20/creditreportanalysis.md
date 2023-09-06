## Credit Risk Classification Analysis Report
-------------------------
### Overview of the Analysis

The purpose of the analysis was to create a model that would help predict the quality of a loan to determine whether it is healthy or high-risk. Using supervised machine learning, the data provided in the csv file contained data of various loans including the loan amount, the interest rates, exisiting debt and accounts of the borrower, as well as total income. 

The instructions provided outlined a clear process to perform the machine learning, which was:
1. Split the data into labels using the loan status', healthy or high-risk, and the rest into features.
2. Spliting the data into training and testing sets
3. Creating a Logistic Regression model using SKlearn was created.
4. The model needed to then fit with the training data
5. Creating predictions that were made with the testing data
6. Finally to evaluate the model by comparing the prediction results with the testing labels.

### Results
- Accuracy Score: 0.99185
- Balanced Accuracy Score: 0.99473
- Precision:
    - Healthy: 1.00
    - High-RiskL 0.85
- Recall:
    - Healthy: 0.99
    - High-Risk: 0.91

Based on the F1-Score of healthy loans as 1.00, the logistic regression model made almost 100% correct predictions almost every time the model was utilizied.
However, the F1-Score of High Risk Loans was not predicted correctly. But the regression model made correct predictions only 85% of the time.

I would use this model for healthy loans, as the results were excellent and were nearly exact to the predictions made. However, for high-risk loabns I would not as there seemed to be less data points and the accuracy of the predictions were not as accurate.
