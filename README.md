- This project contains data scource of retail store data which consists of one fact table :
1 - Transaction fact table  
and 3 diemnsions :
1 - customer dim
2 - product dim
3 - retail dim 

- This is the project requirements : 

- Using ETL tool , we need to create ETL solution to load this data into files or 
data bases based on business need ,you should read source data and make 
transformation on it to serve business need  
Questions: 
1) 
Need data mart that display each transaction for each customer based on 
type of customer “citizen” or “foreign”  with information of it information of 
product and information of stock  which buy  with name file 
“RETAIL_DATA_MART” with transformation upper case of all customer name 
column and display column represent date instead of  dim date table. 
2)  based on question 1 read data mart “RETAIL_DATA_MART” 
Then answer the following business need: 
• Display count of all transaction for each customer for each store  
• Display max profit made by which customer type.  
Illustrate: customer type “foreign” make 5 transactions  
, customer type “citizen” makes 3 transactions. 
So, max profit made by foreign customers.  
Named DataMart “ACTIVATION_SALES_DATA_MART” 
• Based on which customer make profit , give them Bouns  
Equation = Annual_Incomek$* SpendingScore*100

- I provided in this repo the 3 jobs that I created using data stage to answer the required business questions 
