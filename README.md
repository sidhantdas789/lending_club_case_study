# Lending Club Case Study
> A consumer finance company which specialises in lending various types of loans to urban customers needs a risk analysis on existing loan application data which will enable it to identify the key drivers which can be used to flag potential loan defaulters.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
The consumer finance company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

1. If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
2. If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
	
Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 
	
The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc., thereby cutting down the amount of credit loss.
The dataset 'loan.csv' contains information about past loan applicants and whether they ‘defaulted’ or not. This dataset contains various consumer and loan attributes which influences the tendency to default.


## Conclusions
**Key Drivers for loan defaults**
 1. States like CA and NE.
 2. Loan applicants with 1-3 years and 10+ years of experience.
 3. Loan grades with lower credit quality.
 4. Loan applicants with rented accommodation.
 5. Loan purpose – Especially small businesses and debt consolidation
 6. Loan applicants with 60 month’ term (higher loan amounts and interest rates).
 7. Lower credit quality sub-grades, especially F5 (higher loan amounts and interest rates).
 8. High installments for loan applicants with 4+ inquiries in last 6 months.
 9. High DTI.


## Technologies Used
- Pandas - version 1.4.2
- Matplotlib - version 3.5.2
- Seaborn - version 0.11.2


## Acknowledgements
- This project was inspired by the case study assignment we worked on as a group from Upgrad.


## Contact
Created by @sidhantdas789 and @srivay - feel free to contact us!

