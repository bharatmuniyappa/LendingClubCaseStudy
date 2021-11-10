# Lending Club Case Study

Working as consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile.

Two types of risks are associated with the bank’s decision:

1. If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

2. If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

When a person applies for a loan, there are two types of decisions that could be taken by the company:

1. Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

    1. Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

    2. Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

    3. Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

2. Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)


## Table of Contents

* [Abstract](#abstract)
* [Business Objectives](#business-objectives)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## Abstract

Credit risk analysis and credit risk management is important to financial institutions which provide loans to businesses and individuals. 
Credit risk can occur for various reasons such as bank mortgages (or home loans), motor vehicle purchase finances, credit card purchases, installment purchases, and so on. Credit loans and finances have risk of being defaulted. 
To understand risk levels of credit users, credit providers normally collect vast amount of information on borrowers. Some predictive analytic techniques can be used to analyze or to determine risk levels involved on credits, finances, and loans, i.e., default risk levels


## Business Objectives

This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 


## Technologies Used

- Python 3


## Conclusions

- Factor “Purpose” has highest defaulters for “debt_consolidation” reason,  loan approval for “debt_consolidation” should  reduce.
States with state_code CA, FL and NY  has more cases of defaults ,lending Club should control number of loan approval to borrowers. 
- There are a greater number of loans for employee having 1 and 10/10+ yrs exp. Lending club should avoid providing loans to borrowers having employee length around 1 yr and living on Rent. Loan can be approved for higher employee exp like 10/ 10+ yrs as 10+ yrs has high Fully_Paid rate.
- We should reduce providing loans to borrowers seeking more Loan Term period with high DTI (Debt to income ratio).
- We need to avoid approving loans where the funded amount provided by investor and interest rate is more.
- Reduce approving loans to borrowers with employee length 3, 5 ,7 and 10  having grade 'G’ with high interest rate which might make a loss.
- Avoid approving loans to borrowers taking  longer term loan (around 60) and having high monthly installment amount.


## Acknowledgements

- I would like to thank Upgrad and IIT-B for giving us this opportunity to work on Lending Club Case Study. We worked for this case study as a group of 2 and completed without taking any refernce.


## Contact
* [Bharat M](https://github.com/bharatmuniyappa/)
* [Puneet Bansal](https://github.com/puneetba2188/)