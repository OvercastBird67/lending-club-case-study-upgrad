# lending-club-case-study-upgrad

## Members in the group:
- Sahadev Sawant
- Soumya Subhra Bhowmik (Git-hub link: https://github.com/SamSB94)

## Problem Statement

## Business Understanding

You work for a __consumer finance company__ which specialises in lending various types of loans to urban customers. When the company receives a loan application, the comapny has to make a decision for loan approval based on the applicant's profile. Two __types of risks__ are associated with the bank's decision:
  - If the applicant is __likely to repay the loan__, then not approving the loan results in a __loss of business__ to the company
  - If the applicant is __not likely to reapy the loan__, i.e. he/she is likely to default, then approving the loan may lead to a __financial loss__ for the company

The data given below contains the information about past loan applications and wether they 'defaulted' or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of the loan, lending (to risky applicants) at a higher interest rate, etc.

In this case study, you will use EDA to understand how __consumer attributes__ and __loan attributes__ influence the tendency of default.

![Loan_image](https://user-images.githubusercontent.com/83507214/162672287-f9f220bf-9e4e-4f39-88c9-8af48d5697d4.png)

When a person applies for a loan, there are __two types of decisions__ that coiuld be taken by the company:

1. __Loan accepted:__ If the company approves the loan, there are 3 possible scenarios described below:
  - __Fully paid:__ Applicant has fully paid the loan (the principal and the interest rate)
  - __Current:__ Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
  - __Charged-off:__ Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has __defaulted__ on the loan.

2. __Loan rejected:__ The company had rejected the loan (because the candidate does not meet their requirments etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available wiith the company (and thus in this dataset)

## Business Objectives

This company is the largest online loan marketplace, facilitating personal loans, business loans and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.

Like most other lending companies, lending loans to 'risky' applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, norrowers who __default__ cause the largest amount of loss to the leaders. In this case, the customers are labelled as 'charged-off' are the 'defaulters'.

If one is able to indentify these risky loan appliactions, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, the comapny wants to understand the __driving factors__ (__or driver variables__) behind loan default, i.e. the variables which are strong indicators of default. The comapny can utilise this knowledge for its portfolio and risk assessment.

To develop your understanding of the domain, you are advised to independently research a little about risk analytics (understanding the types of variables and their significane should be enough).

## Data Understanding

The dataset and the data dictionary is included in the __data__ folder.

## Results Expected:

1. Write all your code in one well-commented Python file; briefly mention the insights and observations from the analysis.
2. Present the overall approach of the analysis in a presentation
- Mention the problem statement and the analysis approach briefly
- Explain the results of univariate, bivariate analysis etc. in business terms
- Include visualisaztions and summarise the most important results in the presentation.
