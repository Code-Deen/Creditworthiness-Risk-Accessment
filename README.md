# Creditworthiness-Risk-Accessment
This project accesses the risk and credit worthiness of applicants
# Explanation of the Dataset
The definition of the variables are as follows;

person_age: The age of the borrower when securing the loan.

person_income: The borrower’s annual earnings at the time of the loan.

person_home_ownership: Type of home ownership of the applicant; Rent: The borrower is currently renting a property. Mortgage: The borrower has a mortgage on the property they own. Own: The borrower owns a home outright. Other: Other categories of home ownership that may be specific to the dataset.

person_emp_length: The amount of time in years that the borrower has been in employment.

loan_intent: Loan purpose - what applicant (borrower) wants to use the loan for.

loan_grade: A classification system based on credit history, collateral quality, and the likelihood of repayment of the principal and interest. A: The borrower has a high creditworthiness, indicating low risk. B: The borrower is relatively low-risk, but not as creditworthy as Grade A. C: The borrower’s creditworthiness is moderate. D: The borrower is considered to have a higher risk compared to previous grades. E: The borrower’s creditworthiness is lower, indicating a higher risk. F: The borrower poses a significant credit risk. G: The borrower’s creditworthiness is the lowest, signifying the highest risk.

loan_amnt: Total amount of the loan applied for.

loan_int_rate: The interest rate of the loan.

loan_status: Target variable indicating Default as (1) or Non-default as (0). The loan_status variable is a crucial dependent variable. A default occurs when a borrower is unable to make timely payments, misses payments, or avoids or stops making payments on interest or principal owed; 0: Non-default - The borrower successfully repaid the loan as agreed, and there was no default. 1: Default - The borrower failed to repay the loan according to the agreed-upon terms and defaulted.

loan_percent_income: Ratio between the loan amount and the annual income of borrower.

cb_person_cred_hist_length: The number of years of personal history since the first loan was taken by the borrower.

cb_person_default_on_file: Indicates if the person has previously defaulted.

The DataFrame is referred to as "dfrisk"
