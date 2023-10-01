# credit-risk-classification

## Overview of the Analysis
In this Challenge, I used various techniques to train and evaluate a model based on loan risk. I used a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

The dataset had financial information about the loan size, interest rate, borrower's income, debt-to-income ratio and number of accounts. The goal of the model was to predict the loan status (healthy vs. high-risk loans) based on the dataset's features.

As a part of this analysis, I went through below stages:
1. Split the data into training and testing data sets
2. Created the label set (y) and features set (x)
3. Fit a Logistic Regression model by using training data (X_train, y_train)
4. Made prediction using the testing data
5. Evaluated the model's performance using the Confusion Matrix & Classification Report
   
## Results

According to the testing classification report, the model was able to predict healthy loans with 100% accuracy and 85% accuracy for high-risk loans. The model caught 99% of positive cases of healthy loans and 91% of cases of high-risk loans.

## Summary

After completing the evaluation of the model's performance, I would not recommend using this model in real-world practice without further development to increase the model's accuracy. It's vital for the loan approval model to predict high-risk applications to avoid borrower defaulting with accuracy higher than the initial 85% that this model is delivering.

