# coffee-shop-sales
## Project Overview: 
The goal of this project is to analyze sales data from multiple coffee shop locations, gaining insights into transaction trends, customer preferences, and overall business performance. The analysis will be used to help the coffee shop management make data-driven decisions about inventory, product offerings, and store performance.

![image](https://github.com/user-attachments/assets/26c5a17c-3e77-47bb-a755-363009d7fd7c)


## column names:
transaction_id : Unique sequential ID representing an individual transaction

transaction_date : Date of the transaction (MM/DD/YY)

transaction_time : Timestamp of the transaction (HH:MM:SS)

transaction_qty : Quantity of items sold

store_id : Unique ID of the coffee shop where the transaction took place

store_location : Location of the coffee shop where the transaction took place

product_id : Unique ID of the product sold

unit_price : Retail price of the product sold

product_category : Description of the product category

product_type : Description of the product type

product_detail : Description of the product detail


## Updated Key Components of the Dataset:
* Size (size):The size of the product (e.g., small, medium, large).

* Total Bill (total_bill):The total amount spent during the transaction (calculated as transaction_qty * unit_price).

* Month Name (month_name):The name of the month when the transaction occurred (e.g., January, February, etc.).

* Day Name (day_name):The name of the day of the week when the transaction occurred (e.g., Monday, Tuesday, etc.).

* Hour (hour):The hour (in 24-hour format) of the day when the transaction took place (extracted from transaction_time).

* Day of the Week (day_of_week):The numerical representation of the day of the week (e.g., 0 = Monday, 1 = Tuesday, etc.).

* Month Number (month_number):The month of the transaction represented as a number (e.g., January = 1, February = 2, ..., December = 12).

  ## Business Insights
  Our analysis yielded valuable business insights

  * Analyzed monthly,yearly trends by total_bill to understand revenue fluctuations and seasonal sales patterns.
    
  * Compared product_type against total_bill to evaluate revenue contribution of different product offerings.
 
  * Evaluated product_category and total_bill to identify top-performing categories and their contribution to overall revenue.

  * Analyzed size vs total_bill to assess how product sizes impact overall revenue and customer spending behavior.

## Conclusion
This coffee shop sales analysis project provides a comprehensive framework for understanding sales trends, customer preferences, and operational efficiencies within a coffee shop environment. By integrating key data points, such as transaction details, product information, and time-based features (e.g., month, day, hour), the analysis offers actionable insights to drive business decisions.
  
  
