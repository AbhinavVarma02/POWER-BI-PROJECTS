In this mini project, I explored DAX (Data Analysis Expressions) to create custom measures, calculated columns, and derive insights from data in Power BI.

Steps I Followed:
1.Explored the Data Model
Looked at two tables: Apocalypse Sales (sales transactions) and Apocalypse Store (product details).
Verified their relationship via Product ID for use in DAX calculations.

2.Created a Basic Measure using DAX
Added a measure to count the number of sales using COUNT(Order ID).
Built a simple table visualization to see which customers placed the most orders.

3.Summarized Product Sales
Created a measure using SUM(Units Sold) to analyze which product had the highest sales volume.
Used this measure in a visualization to spot best-selling products.

4.Explored SUM vs SUMX Differences
Used SUM(Price - Production Cost) * SUM(Units Sold) to calculate profit, but realized it aggregated incorrectly.
Switched to SUMX for row-wise calculations, ensuring accurate per-product profits.
Compared results of SUM vs SUMX to understand the difference between aggregators and iterators.

5.Worked with Date Functions
Used the WEEKDAY(Date Purchased,2) function to extract the day of the week for each transaction. 2 represents monday as 1 and sunday as 7.
Created a bar chart to analyze if sales varied by day.

6.Implemented an IF Statement in DAX
Created a calculated column using IF(Units Sold > 25, "Big Order", "Small Order").
Categorized orders based on size and added this to the report for quick insights.

7.Finalized Insights and Next Steps
Reviewed the DAX calculations to confirm accuracy.
Saved the project, preparing for more advanced DAX applications in future dashboards.
