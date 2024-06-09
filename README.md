# Enhancing_Direct_Marketing_with_Predictive_Analytics
This project develops predictive models to optimize direct marketing strategies by identifying customers most likely to respond. Classification techniques such as decision trees and logistic regression are employed to improve targeting accuracy and reduce marketing costs.


Project Objective:
The primary objective of this project is to develop and evaluate multiple classification models to predict customer responses to direct mail marketing campaigns. The target is to identify profitable customers, particularly focusing on lapsing customers (those who made their last purchase 13 to 24 months ago), to justify the substantial costs associated with printing and mailing high-quality catalogs.

Data Utilization:
The analysis utilizes two datasets:

dmtrain.csv: Contains historical data on 2,000 customers who have previously responded to mail campaigns, detailing their purchase behaviors and response rates.
dmtest.csv: Used for testing the developed models by predicting customer responses.
Variables:
Key variables include customer ID, number of orders in the last 24 months, total order amount, time elapsed since the last order, order frequency, order amount categories, and a binary response variable indicating whether the customer responded to the campaign.

Methodological Approach:
The project employs various machine learning techniques to achieve its objectives:

Decision Trees: Construction and pruning of decision trees to identify optimal depths based on accuracy, using entropy as the metric and 10-fold cross-validation.

Random Forests: Development of random forest classifiers using the optimal tree depths identified, comparing models based on 100 trees and 50 trees to evaluate performance.

K-Nearest Neighbors (KNN): Selection of the best 'k' values through cross-validation, testing a range of values to determine the one providing the highest accuracy.

Logistic Regression: Application of logistic regression both as a cross-validated model and on the entire training dataset to predict responses and compare against other models.

Model Evaluation:
Each model's performance is rigorously assessed through 10-fold cross-validation. The project determines the most effective model by comparing the accuracy of decision trees, random forests, KNN, and logistic regression models.
