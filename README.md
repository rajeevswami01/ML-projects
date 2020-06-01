# ML-projects

Objective:
----------
Given a Bank customer, build a neural network based classifier that can determine whether they will leave or not in the next 6 months.

Context:
-------
Businesses like banks which provide service have to worry about problem of 'Churn' i.e. customers leaving and joining another service provider. It is important to understand which aspects of the service influence a customer's decision in this regard. Management can concentrate efforts on improvement of service, keeping in mind these priorities.

Data Description:
-----------------
The case study is from an open-source dataset from Kaggle.
The dataset contains 10,000 sample points with 14 distinct features such as CustomerId, CreditScore, Geography, Gender, Age, Tenure, Balance etc.
Link to the Kaggle project site:
https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling

Step Followed:
The points distribution for this case is as follows:
1. Read the dataset
2. Drop the columns which are unique for all users like IDs 
3. Distinguish the feature and target set 
4. Divide the data set into training and test sets 
5. Normalize the train and test data 
6. Initialize & build the model. Identify the points of improvement and implement the same the same.
7. Predict the results using 0.5 as a threshold 
8. Print the Accuracy score and confusion matrix 
