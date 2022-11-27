# Loan Default Prediction

A person’s creditworthiness is often associated (conversely) with the likelihood they may default on loans. Looking at data on loan applicants, useful insights are extracted to guide a business towards decisions. 

The data is about 1000 loan applications, along with a certain set of attributes about the applicant itself, and whether they were considered high risk. <br> 
**Note** : It is worse to state an applicant as a low credit risk when they are actually a high risk

### Dataset Description

The dataset has two files:

1. `applicant.csv`: This file contains personal data about the (primary) applicant
- Unique ID: `applicant_id` (string)
- Other fields:
    - Primary_applicant_age_in_years (numeric)
    - Gender (string)
    - Marital_status (string)
    - Number_of_dependents (numeric)
    - Housing (string)
    - Years_at_current_residence (numeric)
    - Employment_status (string)
    - Has_been_employed_for_at_least (string)
    - Has_been_employed_for_at_most (string)
    - Telephone (string)
    - Foreign_worker (numeric)
    - Savings_account_balance (string)
    - Balance_in_existing_bank_account_(lower_limit_of_bucket) (string)
    - Balance_in_existing_bank_account_(upper_limit_of_bucket) (string)

2. `loan.csv`: This file contains data more specific to the loan application
- Target: `high_risk_application` (numeric)
- Other fields:
    - applicant_id (string)
    - Months_loan_taken_for (numeric)
    - Purpose (string)
    - Principal_loan_amount (numeric)
    - EMI_rate_in_percentage_of_disposable_income (numeric)
    - Property (string)
    - Has_coapplicant (numeric)
    - Has_guarantor (numeric)
    - Other_EMI_plans (string)
    - Number_of_existing_loans_at_this_bank (numeric)
    - Loan_history (string)