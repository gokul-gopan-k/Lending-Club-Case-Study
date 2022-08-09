# Lending club 
> Lending club is the application to find largest source of financial loss for the company in terms of Charged off (Who not able to completely return the loan amount) and who those apply for the loan but for some reason not approved by the company. The main objective of this case study is to find the risky applicants who refuse to return the loan amount for any reason or silently run away . So by finding the key factor variables for that so we can reduce the credit loss. So we performed an analysis to understand the driving variables so company can utilise this knowledge and can reduce the credit loss by below use cases
#### 1> By our driving variable company can easily find the loan defaulter 
#### 2> By our driving variable company can easily find the borrower list who can return the loan amount. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
The main objective of this study to findout the borrower who could be defaulter. We followed below steps to complete this process. 

#### 1> Data Cleaning
#### 2> Univariate Analysis
#### 3> Segmented Univariate analysis
#### 4> Bivariate Analysis
#### 5> Information Content Analysis
#### 6> Result

### Data cleaning :- 
    1> In this process first we caculate the data tried to findout missing values. So we removed the column which have 
       80% + null 
    2> We removed the column which have only one unique value
    3> We removed customer behaviour variables because they are not available at the time of loan application. 
    4> We findout the outliers which are not usefull. 
### Univariate Analysis :- 
    Univariate analysis is the simplest form of analyzing data. Uni means one, so in other words the data has only one 
    variable. Univariate data requires to analyze each variable separately.
### Segmented Univariate analysis:-
    Segmented Univariate analysis is the process to select one varaible and segmented it with other call segmented 
    univariate analysis . i.e In our case if we check the purpose of borrower with univariate now we can divide it
    with the grade now we can see for one purpose there are different percentage for different grade that's call 
    segmented univariate analysis. 
### Bivariate analysis :- 
    In this case we can compare two variables with the target variable so we can find the percentage with compare to 
    the other variable. i.e. In our case loan amount and interest rate with the target variable here we can find for
    high amount with high percentage more chances of charged off. 
#### Information Content Analysis
     In this case, we see which feature or feature combinations have highest information content ie impact on target variables.
    
The business problem is that company approving the loan also for the borrower which have highly chances of charged off and other side they are rejecting the application which can fully paid the loan. So in our study we found the factor variable which can help to find out the right borrower so it can help the company to reduce the credit loss. 

We are using Lending club data set avaiable in CSV format. 


## Technologies Used
- Notebook - version 6.4.8
- pandas - It is used for data cleaning and analysis. 
- numpy - NumPy is a Python library used for working with arrays. It also has functions for working in domain of linear algebra, and matrices like to get mean,median etc. 
- seaborn  - Seaborn is a library for making statistical graphics in Python.
- matplotlib.pyplot  - Matplotlib is a cross-platform, data visualization and graphical plotting library for Python.



## Conclusions
1) Higher risk grades(above E) should be avoided as they have higher chance of defaulting. Moving from grade E to B reduce default rate by 12%. Grades F and G strictly to be avoided as default rate is above 30%.
2) Within a grade, low risk subgrade should be preferred.For example, moving from D4 to D1 reduce default rate by 5%.
3) High loan amounts (> 35k)in risky grades should be strictly avoided as they have one of the highest rate of default.For example, high loan amounts to grade F result in default rate  of more than 30%.
4) High loan amounts (>35k) should preferably not be given to people with multiple public bankruptcies as this combination leads to one of highest default rate. For example, high loan amounts to people of one public bankruptcy gave close to 30% default rate while all those with two public bankruptcies defaulted.
5) Among purposes, small business loans should be restricted (>25% default rate) and promote low defaulting purposes like credit card and car(close to 10% default rate)
6) Among purpose, high loan amounts(>35k) should be restricted in small business loans category as default rate is close to 30%.
7) Loans at higher interest rate have higher chance of defaulting. Interest rate till 12% is acceptable but anything above %12 should be restricted as it result in default rate of20%. But this can reduce profits from interest receipts hence as a tradeoff medium interest rate of 8-12% can be suggested which have considerably lower 11% default rate. 
8) People with zero derogatory public record should be preferred and those with even one maybe avoided as their default rate is 22%. 
9) Borrowers with higher debt to income ratio are more likely to default (about 17%). Hence loans be approved only for people with low debt to income in range less than 10% dti.
10) Loans at shorterm term(3 years) should be preferred over longer term. For loans at higher term , default rate is almost 15% more than those of shorter term.
11) Longer term loans (5 years)  should be avoided also for borrowers with lower annual income of less than 40k as they result in default rate of 32%.
12) Lower risk grade have been given low or medium interest rate(<12%) this lead to less than 10% default. Hence this practice should be continued.
13) Purposes like credit card and wedding can be  charged at  medium interest rate(8-12 %) can increase business as default rate is less than 10%. If priority is to reduce default rate over higher interest payments  then we can charge low interest rate (<8%) as default rate is less than 5% for these categories at low interest rate.
14) Borrowers with high annual income(>5 lakh) can be  charged at lower interest rate(<8%) as default rate is close to 3% only.
15) To to reduce default rate in high loan amounts (>35k) should be given at low interest rate(<8%) as default rate is low and less than 5%. 

## Acknowledgements
    This project was inspired by Upgrade.
    References
    We referenced the google (Technical problems) and Lending case study live class. 

### Contributors
1)Gokul Gopan k : 
[@githubusername] - https://github.com/gokul-gopan-k 
2)Sarvesh kumar upadhyay:
[@githubusername] - https://github.com/sarves150 

## Contact
Created by
[@githubusername] - https://github.com/gokul-gopan-k 
feel free to contact me!

