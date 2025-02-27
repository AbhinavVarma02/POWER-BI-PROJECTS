In this mini project, I have explored Power Query in Power BI to clean, transform, and structure data for better visualization and analysis.

Steps I Followed:

1.Loaded Data into Power Query
Imported the Apocalypse Food Prep Excel file.
Selected both Pivot Table and Purchase Overview sheets for transformation.

2.Cleaned Up the Data
Removed unnecessary top rows containing null values.
Used "First Row as Headers" to set proper column names.
Changed data types where needed (e.g., converting text to date and decimal for costs).

3.Filtered and Removed Unwanted Rows/Columns
Removed subtotal and grand total rows using text filters.
Deleted the Grand Total column since it wasn't needed for visualization.

4.Unpivoted Columns for Better Structure
Converted date columns into rows using Unpivot Columns to make the data more usable.
Renamed key columns (Location → Store, Value → Product Cost).

5.Finalized the Transformation
Verified the cleaned-up dataset.
Clicked "Close & Apply" to save and load the transformed data into Power BI.
