# Model-Improvement
## Repository for files related to ML Model Improvement techniques

**Data Background** 

The global financial crisis of 2007-2008 has highlighted the importance of transparency and rigor in 
banking practices. As the availability of credit has been limited, banks are increasingly tightening 
their lending systems and turning to machine learning to more accurately identify risky loans.In this 
section, you will develop a simple credit approval model using decision trees. We will also see how 
the results of the model can be tuned to minimize errors that result in a financial loss for the 
institution. 

The credit dataset includes 1,000 examples of loans, plus a combination of numeric and nominal 
features indicating characteristics of the loan and the loan applicant. A class variable indicates 
whether the loan went into default. 

***

**Data Dictionary** 

checking_balance: Status of existing checking account 
A11 : ... < 0 DM 
A12 : 0 <= ... < 200 DM 
A13 : ... >= 200 DM / salary assignments for at least 1 year 
A14 : no checking account 
months_loan_duration 

credit_history: 
A30 : no credits taken/ all credits paid back duly 
A31 : all credits at this bank paid back duly 
A32 : existing credits paid back duly till now 
A33 : delay in paying off in the past 
A34 : critical account/ other credits existing (not at this bank) 

purpose: 
A40 : car (new) 
A41 : car (used) 
A42 : furniture/equipment 
A43 : radio/television 
A44 : domestic appliances 
A45 : repairs 
A46 : education 
A47 : (vacation - does not exist?) 
A48 : retraining 
A49 : business 
A410 : others 

amount: credit amount 
savings_balance : 
A61 : ... < 100 DM 
A62 : 100 <= ... < 500 DM 
A63 : 500 <= ... < 1000 DM 
A64 : .. >= 1000 DM 
A65 : unknown/ no savings account 

employment_duration: Present employment since 
A71 : unemployed 
A72 : ... < 1 year 
A73 : 1 <= ... < 4 years 
A74 : 4 <= ... < 7 years 
A75 : .. >= 7 years 

percent_of_income: Installment rate in percentage of disposable income 

years_at_residence 

age 

other_credit: Other installment plans 
A141 : bank 
A142 : stores 
A143 : none 

housing: 
A151 : rent 
A152 : own 
A153 : for free 

existing_loans_count: Number of existing credits at this bank 

job: 
A171 : unemployed/ unskilled - non-resident 
A172 : unskilled - resident 
A173 : skilled employee / official 
A174 : management/ self-employed/highly qualified employee/ officer 

dependents: Number of people being liable to provide maintenance for 

phone: 
A191 : none 
A192 : yes, registered under the customer name 

default : no and yes 
 
