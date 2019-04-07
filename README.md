# Prudential-Life-Insurance-Assessment-using-Machine-Learning-Algorithms-built-using-Python
Can you make buying life insurance easier?

## Welcome to my First Kaggle Competition Repository!!
Hope that you'll learn something from this!

## Introduction
![Prudential Logo](https://storage.googleapis.com/kaggle-competitions/kaggle/4699/logos/front_page.png)<br>
This is from the [Kaggle's Prudential competition website](https://www.kaggle.com/c/prudential-life-insurance-assessment/overview) :<br>
<br>
Picture this. You are a data scientist in a start-up culture with the potential to have a very large impact on the business.
Oh, and you are backed up by a company with 140 years' business experience.<br><br>
Curious? Great! You are the kind of person we are looking for.<br><br>
Prudential, one of the largest issuers of life insurance in the USA, is hiring passionate data scientists to join a
newly-formed Data Science group solving complex challenges and identifying opportunities. The results have been impressive
so far but we want more.<br>
#### What's the Challenge?
In a one-click shopping world with on-demand everything, the life insurance application process is antiquated.
Customers provide extensive information to identify risk classification and eligibility, including scheduling medical exams,
a process that takes an average of 30 days.<br><br>
The result? People are turned off. That’s why only 40% of U.S. households own individual life insurance.
Prudential wants to make it quicker and less labor intensive for new and existing customers to get a quote while maintaining
privacy boundaries.<br><br>
By developing a predictive model that accurately classifies risk using a more automated approach, you can greatly impact public
perception of the industry.<br><br>
The results will help Prudential better understand the predictive power of the data points in the existing assessment,
enabling us to significantly streamline the process.

## Data Description
In this dataset, you are provided over a hundred variables describing attributes of life insurance applicants. 
The task is to predict the "Response" variable for each Id in the test set. "Response" is an ordinal measure of risk that has 8 levels.
### File descriptions
* **train.csv** - the training set, contains the Response values
* **test.csv** - the test set, you must predict the Response variable for all rows in this file
* **sample_submission.csv** - a sample submission file in the correct format
### Data fields
| **Variable**     | **Description** |
| ------------------ | ----------------|
| Id           |A unique identifier associated with an application.|
| Product_Info_1-7 |A set of normalized variables relating to the product applied for|
| Ins_Age      |Normalized age of applicant|
| Ht           |Normalized height of applicant|
| Wt           |Normalized weight of applicant|
| BMI          |Normalized BMI of applicant|
|Employment_Info_1-6 | A set of normalized variables relating to the employment history of the applicant.|
|InsuredInfo_1-6|	A set of normalized variables providing information about the applicant.
|Insurance_History_1-9|	A set of normalized variables relating to the insurance history of the applicant.
|Family_Hist_1-5	|A set of normalized variables relating to the family history of the applicant.
|Medical_History_1-41 |A set of normalized variables relating to the medical history of the applicant.
|Medical_Keyword_1-48	|A set of dummy variables relating to the presence of/absence of a medical keyword being associated with the application.
|Response	|This is the target variable, an ordinal variable relating to the final decision associated with an application
### The following variables are all categorical (nominal):
Product_Info_1, Product_Info_2, Product_Info_3, Product_Info_5, Product_Info_6, Product_Info_7, 
Employment_Info_2, Employment_Info_3, Employment_Info_5, InsuredInfo_1, InsuredInfo_2, InsuredInfo_3, 
InsuredInfo_4, InsuredInfo_5, InsuredInfo_6, InsuredInfo_7, Insurance_History_1, Insurance_History_2, 
Insurance_History_3, Insurance_History_4, Insurance_History_7, Insurance_History_8, 
Insurance_History_9, Family_Hist_1, Medical_History_2, Medical_History_3, Medical_History_4, 
Medical_History_5, Medical_History_6, Medical_History_7, Medical_History_8, Medical_History_9, 
Medical_History_11, Medical_History_12, Medical_History_13, Medical_History_14, Medical_History_16, 
Medical_History_17, Medical_History_18, Medical_History_19, Medical_History_20, Medical_History_21, 
Medical_History_22, Medical_History_23, Medical_History_25, Medical_History_26, Medical_History_27, 
Medical_History_28, Medical_History_29, Medical_History_30, Medical_History_31, Medical_History_33, 
Medical_History_34, Medical_History_35, Medical_History_36, Medical_History_37, Medical_History_38, 
Medical_History_39, Medical_History_40, Medical_History_41
### The following variables are continuous:
Product_Info_4, Ins_Age, Ht, Wt, BMI, Employment_Info_1, Employment_Info_4, Employment_Info_6, 
Insurance_History_5, Family_Hist_2, Family_Hist_3, Family_Hist_4, Family_Hist_5
### The following variables are discrete:
Medical_History_1, Medical_History_10, Medical_History_15, Medical_History_24, Medical_History_32
### The following variables are dummy variables:
Medical_Keyword_1-48 are dummy variables.

## Jupyter Notebook
The whole project is in this [Jupyter Notebook](https://github.com/Reljod/Prudential-Life-Insurance-Assessment-using-Machine-Learning-Algorithms-built-using-Python/blob/master/Prudential.ipynb)
