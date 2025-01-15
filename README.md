# Axis Bank Customer Churn Analysis
![alt text](https://github.com/ArmanShah025/Bank_Analysis_PowerBI/blob/main/DashboardIMG.png)
## Overview
I developed a Power BI dashboard for Bank Churn Analysis, utilizing Power Query for data cleaning, transformation, and modeling, and DAX to create calculated measures and columns for in-depth insights. The dashboard features interactive visualizations, highlighting key metrics such as churn rates, customer segmentation, and retention trends, providing a dynamic and comprehensive analysis to support strategic decision-making.

## 1)	Data Gathering:

Data assets to pull the data related to Bank customer and associated details.
ActiveCustomer.xlsx
Bank_Churn.csv
CreditCard.xlsx
CustomerInfo.csv
ExitCustomer.xlsx
Gender.xlsx
Geography.xlsx


## Data Dictionary (The complete understanding of Business)

1)	RowNumber—corresponds to the record (row) number and has no effect on the output.

2)	CustomerId—contains random values and has no effect on customer leaving the bank.

3)	Surname—the surname of a customer has no impact on their decision to leave the bank.

4)	CreditScore—can have an effect on customer churn, since a customer with a higher credit score is less likely to leave the bank.

5)	Geography(where the bank is and which location customers are)—a customer’s location can affect their decision to leave the bank.

6)	Gender—it’s interesting to explore whether gender plays a role in a customer leaving the bank.

7)	Age—this is certainly relevant, since older customers are less likely to leave their bank than younger ones.

8)	Tenure—refers to the number of years that the customer has been a client of the bank. Normally, older clients are more loyal and less likely to leave a bank.

9)	Balance—also a very good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances.

10)	NumOfProducts(Bank offer diff products likes FD(fixedDepository), RD(RecurringDeposit), loans, —refers to the number of products that a customer has purchased through the bank. 
{ Which is better RD or FD?
The fixed and recurring deposits are very similar but can be differentiated by how money is invested. High-interest rates and a tax-saving facility are some of the best benefits of an FD. A recurring deposit is best for those who prefer to invest small amounts.}

11)	1HasCrCard—
Denotes whether or not a customer has a credit card. This column is also relevant, since people with a credit card are less likely to leave the bank(because they have to pay back their loans emi etc).
1 represents credit card holder
0 represents non credit card holder

12)	IsActiveMember—active customers are less likely to leave the bank.
1 represents Active Member
0 represents Inactive Member (If you are not doing transaction from debit/credit and doing transaction)

13)	 Estimated Salary—as with balance, people with lower salaries are more likely to leave the bank compared to those with higher salaries.

14)	Exited— whether or not the customer left the bank.
0 represents Retain   (Still they are with the bank)
1 represents Exit

15) Bank DOJ — date when the Customer associated/joined  with the bank




### End To End - TASKS Performed - Life Cycle of a Data Analyst

- Requirement Gathering (BRD / FRD)
- Data Collections (Database / CSV/ Excel)
- Data Modelling
- Data Cleaning / Data Pre-processing
- UI Report (Charts / Custom Charts)
- Additional Information (DAX Calculations)
