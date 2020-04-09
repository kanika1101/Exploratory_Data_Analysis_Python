This is a university project carried as a case study for upGrad and IIIT-B

# Exploratory Data Analysis in Python - Bank Loan Case Study

This case study aims to identify patterns which indicate if a client has difficulty paying their installments which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. This will ensure that the consumers capable of repaying the loan are not rejected. 

#### Identification of such applicants using EDA is the aim of this case study.

 
In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment.


### Solution Overview 

Exploratory data analytics requires understanding of data and how different variables are correlated. To understand the data using python data visualization and pandas we will be taking a case study of bank loan applications data.

The bank applications data has a dependent variable named TARGET variable whose value is 1 when the applicant is a defaulter and have missed the replayment of loan. For other applicants this value will be 0. All other columns in the data are considered independent variables.

We will explore the data step by step, visualize the data, create count/count percentage and summary tables and see how different variables like age, credit ratings, income etc of the applicant varies with the TARGET variable.

The following steps will be covered in the tutorial

Getting the data ready

1.1 Understanding the data
1.2 Cleaning data by dropping unwanted rows and columns
1.3 Handling missing values
1.4 Handling outliers
1.5 Changing the data types of columns
1.6 Changing column names into meaningful ones for analysis.
1.7 Creating derived variables and binning the data.
1.8 Understanding the data imbalance

Data Analysis
2.1 Univariate Analysis
2.1.1 Categorical
2.1.2 Numerical
2.2 Bivariate Analysis
2.2.1 Categorical & Categorical
2.2.2 Numerical & Numerical
2.2.3 Categorical & Numerical

After performing the above analysis, we will be arriving at the driving factors behind the loan defaults

