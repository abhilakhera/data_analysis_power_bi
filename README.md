**Business Case**

This case study is about a company named Blu which has successful ventures into multiple product ranges as well as leaders in real estate business. The company’s global business head wants to use a dashboard that helps to track key metrics about their nine business unit managers (executives), products, Sales, Quantities sold, and gross margins (GM).

Download the dataset from : 

https://drive.google.com/drive/folders/1eplz7vmnNG67KECek0CUAyFaVxm4ngc2?usp=sharing

**Step 1: Extract-Load-Transform [ELT]**

After Extracting and Loading the dataset, transform the data as per the requirement.
- Clean unused or erroneous rows [if there are any]
- Fixed the datatype issues [if any]
- Fix the other issues [if any]

**Step 2: Data Modeling**

As the database is normalized, we see lots of tables representing specific data points. At this point, having a proper relationship among the table is of utmost importance.
So we create the relationship among the tables.

**Step 3:  Add Visual Level Filters with Slicers**

All of the options in the slicers have multi-selection and “Select All” option.

**Step 4: Donut Chart**

Plot Donut Chart to display the % contribution of Gross Margin and Total Gross Margin
Total Sales is calculated using the below formula:
Total Sales =  (Sum_Markdown_Sales_Dollars * Sum_Markdown_Sales_Units) + (Sum_Regular_Sales_Dollars * Sum_Regular_Sales_Units)

**Step 5: Filter**

Filter “Blank”  month ID from the entire Dashboard and Ignore Negative Gross margin transactions
Don’t show the “Blank” month id in any of the visuals.
Also, Filter out the transactions with Gross margins lesser than 0 in your analysis. Only those transactions that have gross margins greater than or equal to 0 must be considered.

**Step 6: Table Chart**
Create the following table chart, which shows 
- Sum of Gross Margin for Scenario 1
- Sum of Gross Margin for Scenario 2
- Gross Percentage

All the calculation must be based on Months of Sales datasheet.
- Scenario 1 occurs when due to lesser inventory, all the ordered goods were not delivered to the customer.
- Scenario 2 occurs when all the ordered goods were delivered to the customer, thanks to optimized inventory levels maintained. 
Management wants to know that out of total gross margin availed, what percentage is due to the transactions that occurred due to Scenario 1. Thus Gross Percentage is obtained by dividing Gross Margin of Scenario 1 by Sum of Gross Margin Amount, subsequently multiplying with 100.

**Step 7: Create a drill down capability to analyze Total rent obtained on a Time dimension** 


Download the solution from:

https://drive.google.com/file/d/1hsFotuPbCCAZaENXppmvp5f7kMAR8TeT/view?usp=sharing



