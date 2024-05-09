# All-Occasion-Gift-Shop
Basic PowerBI Dashboard

This is a transnational dataset containing all transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers. 

The available dashboard provides data analysis and visualization for this data set, including the number of transactions, no. of active clients (new and recurrent), and churn rate across time (weekly, monthly, and annually). 

The “churn rate” was calculated based on the following definition: 
(Lost customers/Total customers at a certain period) *100

Due to a lack of information about previous years. The annual rate was calculated by using the average losses per month.
As for the monthly & weekly rates, I used the available purchase date to estimate the number of lost customers by gathering the last contact date for each customer, i.e., I took the latest purchase date for each customer and grouped it into months. Then I subtracted the total count of each month from the total of the following month...

N.B. The churn rates were calculated externally in two separate CSV files “month_churn” and “week_churn”. The file results were renamed “month_churn_rate” and “week_churn_rate”.
