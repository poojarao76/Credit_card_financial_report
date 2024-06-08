# Credit_card_financial_report

## Project Objective

- To develop a comprehensive credit card weekly dashboard that provides real-time insights into key performance metrics and trends, enabling stakeholders to monitor and analyze credit card operations effectively.

## Dataset

- [Customer.csv](https://github.com/poojarao76/Credit_card_financial_report/blob/main/customer.csv)
    - Client_Num: A unique identifier for each customer.
    - Customer_Age: The age of the customer.
    - Gender: The gender of the customer.
    - Dependent_Count: The number of dependents the customer has.
    - Education_Level: The highest level of education attained by the customer.
    - Marital_Status: The marital status of the customer.
    - state_cd: The state code where the customer resides.
    - Zipcode: The postal code of the customer's residence.
    - Car_Owner: Indicates whether the customer owns a car (yes/no).
    - House_Owner: Indicates whether the customer owns a house (yes/no).
    - Personal_loan: Indicates whether the customer has taken a personal loan (yes/no).
    - contact: The preferred method of contact for the customer (e.g., email, phone).
    - Customer_Job: The occupation or job title of the customer.
    - Income: The income of the customer.
    - Cust_Satisfaction_Score: The satisfaction score given by the customer.

- [credit_card.csv](https://github.com/poojarao76/Credit_card_financial_report/blob/main/credit_card.csv)
    - Client_Num: A unique identifier for each customer.
    - Card_Category: The category of the credit card (e.g., rewards, travel, cashback).
    - Annual_Fees: The annual fees associated with the credit card.
    - Activation_30_Days: Indicates if the card was activated within 30 days of issuance.
    - Customer_Acq_Cost: The cost incurred to acquire the customer.
    - Week_Start_Date: The start date of the week for the transaction or activity.
    - Week_Num: The week number within the year.
    - Qtr: The quarter of the year (Q1, Q2, Q3, Q4).
    - current_year: The current year of the transaction or data.
    - Credit_Limit: The credit limit of the card.
    - Total_Trans_Amt: The total transaction amount within a specified period.
    - Total_Revolving_Bal: The total revolving balance on the card.
    - Total_Trans_Amt: The total transaction amount within a specified period.
    - Total_Trans_Vol: The total volume of transactions within a specified period.
    - Avg_Utilization_Ratio: The average credit utilization ratio.
    - Use Chip: Indicates whether the card has a chip (yes/no).
    - Exp Type: The type of expenses or transactions.
    - Interest_Earned: The interest earned from the card.
    - Delinquent_Acc: The number of delinquent accounts associated with the customer. 


## Key Takeaways

New Columns:

- For Customers Table:
  
   - To make the Age and Income columns more presentable in visualizations, I have created new columns dividing them into groups:

      ![image](https://github.com/poojarao76/Credit_card_financial_report/assets/132984172/07eb6c96-ae28-4d72-8244-7b4e796052ee)

- For Credit Card Table:

  - Created a revenue column:

      ![image](https://github.com/poojarao76/Credit_card_financial_report/assets/132984172/ff4878dc-c0f1-4c6d-bac2-64a9b956cf0e)

  - Created a week number column:

      ![image](https://github.com/poojarao76/Credit_card_financial_report/assets/132984172/ae3434a7-3bd5-4481-bd0f-d9b6828105df)

## Project Insights:

- Overall revenue: $23.4 million
- Total interest earned: $3 million
- Total transaction amount: $18.9 million
  
- Revenue by gender:
  
  - Male customers: $12.62 million
  
  - Female customers: $10.82 million
  
- Top contributing card categories: Silver and Blue cards in transactions
- Overall activation rate: 58.29%
- Overall delinquency rate: 6.27%
