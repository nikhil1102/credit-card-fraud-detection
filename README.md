# credit-card-fraud-detection

## Project Introduction
It is often that the data we retrieve have imbalanced label and we are asked to make classification. These scenarios are troublesome since not only the models we usally use bring poor result, but also the evaluation metric we often used, accuracy, is not adequate for imbalanced data sets due to the impact of the minority class. This project aims to demonstrate some techniques used to combat these situations, such as resampling or cluster before predicting, as well as using PR (Precision-Recall) curve to evaluate model. The approaches for the project are :

1. Randomly split the dataset into train, and test set.
2. Do basic EDA and feature engineering.
3. Resample the dataset.
4. Train on resampled train set then predict and evaluate with validation set.
5. Try other different models.
6. Find the optimised threshold of the  model.
7. Compare the difference between the predictions and choose the best model.
8. Predict on test set to report final result.

## Data source: https://www.kaggle.com/mlg-ulb/creditcardfraud

## Medium Articles:

### Part 1:
Credit Card Fraud Detection: In-Depth Study: Data Preparation (https://nikhilthapa12.medium.com/credit-card-fraud-detection-in-depth-study-data-preparation-ecd74da3a1c7)
### Part 2: 
Credit Card Fraud Detection: In-Depth Study: Evaluating the Classification Model(https://medium.com/analytics-vidhya/credit-card-fraud-detection-in-depth-study-evaluating-the-classification-model-a3680a5a5897)
### Part 3: 
Credit Card Fraud Detection: Logistic Regression (https://medium.com/analytics-vidhya/credit-card-fraud-detection-logistic-regression-121d2dd35e2d)
### Part 4: 
Credit Card Fraud Detection: Classification Models and Neural Networks (https://medium.com/analytics-vidhya/credit-card-fraud-detection-classification-models-and-neural-networks-187749572fa6) 
