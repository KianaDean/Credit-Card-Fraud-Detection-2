# Credit-Card-Fraud-Detection-2
Predictive Models and a PowerBI Dashboard to predict credit card fraud

## The Problem
Contactless payment is on the rise. The adoption rate was acclerated during the pandemic. With the increased use in credit cards this opens up the window to more fraudulent transactions. Due to the sheer amount of transactions companies need a way to detect fraud as soon as it happens.

## The Solution
This is where predictive models can be helpful. By feeding in variables, models can be built to analyze the features of a transaction and mark it as fraud or not fraud. This allows companies to catch the fraud sooner rather than later because fraud transactions can have a significant impact on the business.

## The Data
The dataset was simulated using Python. The code used is from the [Fraud Detection Handbook](https://fraud-detection-handbook.github.io/fraud-detection-handbook/Chapter_3_GettingStarted/SimulatedDataset.html) with a couple adjustments made.

* 1,000 customers
* 5,000 terminals
* 30 days of transactions for the month of April 2018

## Steps Taken
1. Load the data into R and complete Exploratory Data Analysis
2. Ran three models to evaluate which out of three would be the best for predicting credit card fraud. Models I ran:
	* CART Decision Trees
	* Logistic Regression
	* Random Forest
3. Model Assessment - looked at the AUC of each model to determine which model would be the best to use. In this case, it was Logistic Regression.
4. Created a PowerBI dashboard to show metrics of the data and transactions

**Tools Used:** Python, R, PowerBI

## Credit Card Fraud Dashboard
![CCTransaction Metrics](https://github.com/KianaDean/Credit-Card-Fraud-Detection-2/blob/main/images/FraudDetectionDashboard.PNG)

![CCTransactions](https://github.com/KianaDean/Credit-Card-Fraud-Detection-2/blob/main/images/TransactionDetails.PNG)
