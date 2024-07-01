# Global Business Overview (GBO)
This case study is about a company named Blu which has successful ventures into multiple product ranges as well as leaders in real estate business. The company’s global business head wants to use a dashboard that helps to track key metrics about their nine business unit managers (executives), products, Sales, Quantities sold, and gross margins (GM)

1. Typically, Extract-Load-Transform [ELT] process is being followed.
After Extracting and Loading the dataset, transform the data as per the requirement.


a) Clean unused or erroneous rows [if there are any]

b) Fixed the datatype issues [if any]

c) Fix the other issues [if any]


2. Data Modeling
   
As the database is normalized, we see lots of tables representing specific data points. At this point, having a proper relationship among the table is of utmost importance.
Please create the relationship among the table if there isn’t any.

3. Total Sales is calculated using the below formula:
 
Total Sales =  (Sum_Markdown_Sales_Dollars * Sum_Markdown_Sales_Units) + (Sum_Regular_Sales_Dollars * Sum_Regular_Sales_Units)

4.  Filter “Blank”  month ID from the entire Dashboard and Ignore Negative Gross margin transactions. Don’t show the “Blank” month id in any of the visuals.
Also, Filter out the transactions with Gross margins lesser than 0 in your analysis. Only those transactions that have gross margins greater than or equal to 0 must be considered.

5. Total Quantity(Units) will be based on summation of Sum_Markdown_Sales_Units and Sum_Regular_Sales_Units.
 
Management has an interest analysing newly launched Home category for high margin transactions. Home sales must be calculated for total quantity sold for Home Category that has a gross margin amount greater than 10.

6. Create the following table chart, which shows
   
a) Sum of Gross Margin for Scenario 1

b) Sum of Gross Margin for Scenario 2

c) Gross Percentage


7. All the calculation must be based on Months of Sales datasheet.
   
Scenario 1 occurs when due to lesser inventory, all the ordered goods were not delivered to the customer.

Scenario 2 occurs when all the ordered goods were delivered to the customer, thanks to optimized inventory levels maintained.

Management wants to know that out of total gross margin availed, what percentage is due to the transactions that occurred due to Scenario 1. Thus Gross Percentage is obtained by dividing Gross Margin of Scenario 1 by Sum of Gross Margin Amount, subsequently multiplying with 100.



