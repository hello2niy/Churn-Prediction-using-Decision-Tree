# Churn-Prediction-using-Decision-Tree

Table of contents

1. Importing required libraries
2. Logistic Regression Model
3. Decision Tree Model
4. Plotting ROC Curve
5. Visualizing Decision tree model
6. Feature Importance

   
Business Objective

A Decision Tree is a supervised learning technique that can be used for both classification and regression problems, but it is mostly preferred for solving classification problems. It is a tree-structured classifier, where internal nodes represent the features of a dataset, branches represent the decision rules, and each leaf node represents the outcome.

It is a graphical representation of all possible solutions to a problem or decision based on given conditions. It is called a decision tree because, similar to a tree, it starts with the root node, which expands on further branches and constructs a tree-like structure. A decision tree asks a question, and based on the answer (Yes/No), it further splits the tree into subtrees.

In our case study, we will be working on a churn dataset. Churned customers are those who have decided to end their relationship with their existing company.
The streaming app is a service-providing company that provides customers with a one-year subscription plan for their product. The company wants to know if the customers will renew the subscription for the coming year or not.

Data Description

The CSV consists of around 2000 rows and 16 columns
Features:
1.	Year
2.	Customer_id - unique id
3.	Phone_no - customer phone no
4.	Gender -Male/Female
5.	Age – age of the customer
6.	No of days subscribed - the number of days since the subscription
7.	Multi-screen - does the customer have a single/ multiple screen subscription
8.	Mail subscription - customer receive emails or not
9.	Weekly mins watched - number of minutes watched weekly
10.	Minimum daily mins - minimum minutes watched
 
11.	Maximum daily mins - maximum minutes watched
12.	Weekly nights max mins - number of minutes watched at night time
13.	Videos watched - total number of videos watched
14.	Maximum_days_inactive - days since inactive
15.	Customer support calls - number of customer support calls
16.	Churn -
●	1- Yes
●	0 - No



Aim

Build a decision tree model on the given dataset to determine whether the customer will churn or not.


Tech stack
	Language - Python
	Libraries - NumPy, pandas, matplotlib, sklearn, pickle, imblearn

Approach
1.	Importing the required libraries and reading the dataset.
2.	Feature Engineering
       Dropping of unwanted columns
3.	Model Building
      Performing train test split
     	Decision tree Model
4.	Model Validation (predictions)
     	Accuracy score
      Confusion matrix
    	ROC and AUC
      Recall score
      Precision score
      F1-score
5.	Feature Importance
      Create a function to find important features
    	Plot the features
