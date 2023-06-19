# Telecom_Churn_Case_Study  

In telecom industry customers are can choose from multiple service provider and customers can quickly switch from one service provider to another. This Project aims to identify the churn customer for the telecom company.

## Table of Contents

- [Business Problem](#business-problem)
- [Data](#data)
- [Methodology](#methodology)
- [Results](#results)
- [Conclusion](#conclusion)
- [Technology used](#Technology used)
- [Contact](#Contact)


## Business Problem

There are multiple telecom companies and customers have a multiple choice available in the market. Due to this customers can switch from one service provider to another service provider quickly. This hopping of customer is known as churn rate. telecon companies has churn rate ranging from 15% - 30%. Therefore it becomes very important for telecom companies to identify the churn rate and retain the customers by giving them lucrative offer.  

## Data

The data set include various data of customers like Their subscription period, type of payment, age, payment method, gender, internet service, monthly charges etc. which explains the behaviours of customers. There was no outlier present in our dataset. There were certain features which were map, certain fatures were one hot encoded and few levels of certain features were deleted for reducing the correlations between the features.

## Methodology

This is a binary classification problem. Here Logistic regression has been used for classifying the churn and non-churn customers. standarad scaler was used for scaling the numeric columns. Auto feature selection technique Recursive Feature Elimination is used to identify the top 15 features and on that top 15 features we applied manual feature selection technique Variance Inflation Factor (VIF) and p-values to identify the best 5 features for our model. confusion matrix was used for identifying the number of rows correctly classify and the AUC-ROC curve was used for choosing the optimal threshold values.

## Results

The AUC-ROC curve area was 0.76. The best features after feature selection were Contract_two_years, tenure, contract_one_year, internet_fiber_service optic, and internetService_No. 

## Conclusion

Here, we had a good AUC-ROC curve area of 0.76. But we need to use a better algorithm for classification purposes. The telecom company should focus on more on customers with a contract of one year. Customers have fiber optic service and with shorter tenure.  

## Technology used 

- pandas - version 1.5.3
- numpy - version 1.22.4
- seaborn - version 0.12.2
- matplotlib - version 3.7.1
- sci-kit learn - version 1.2.2
- statsmodel - version 0.13.5

## Contact

Created by Harshit-tech9 - feel free to contact me at harshitpanchalcie16@gmail.com





