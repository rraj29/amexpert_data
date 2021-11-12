# amexpert_data
XYZ Bank is a mid-sized private bank that includes a variety of banking products, such as savings accounts, current accounts, investment products, credit products, and home loans.

The Bank wants to predict the next set of products for a set of customers to optimize their marketing and communication campaigns.

The data available in this problem contains the following information:

User Demographic Details : Gender, Age, Vintage, Customer Category etc.
Current Product Holdings
Product Holding in Next 6 Months (only for Train dataset)
Here, our task is to predict the next set of products (upto 3 products) for a set of customers (Test data) based on their demographics and current product holdings.


Dataset Description

Train.csv

Customer_ID - Unique ID for the customer 
Gender - Gender of the Customer
Age - Age of the Customer (in Years)
Vintage - Vintage for the Customer (In Months)
Is_Active - Activity Index, 0 :  Less frequent customer, 1 : More frequent customer
City_Category - Encoded Category of customer's city
Customer_Category - Encoded Category of the customer
Product_Holding_B1 - Current Product Holding (Encoded)
Product_Holding_B2 - Product Holding in next six months (Encoded) - Target Column

Test.csv

Customer_ID - Unique ID for the customer 
Gender - Gender of the Customer
Age - Age of the Customer (in Years)
Vintage - Vintage for the Customer (In Months)
Is_Active - Activity Index, 0 :  Less frequent customer, 1 : More frequent customer
City_Category - Encoded Category of customer's city
Customer_Category - Encoded Category of the customer
Product_Holding_B1 - Current Product Holding (Encoded)

