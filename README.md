# Power-BI-Assignment-1-
 Data Transformation &amp; Data Modeling 
1.1.Opened Power BI Desktop. Selected Home → Get Data → Text/CSV.
Imported the List of Orders.csv file.
Imported Order Details.csv and Sales Target.csv into Power Query Editor.
Method Used: Get Data and Power Query Editor.
2. Selected the List of Orders query.
Opened the Home tab.
Selected Keep Rows → Keep Top Rows.Entered 500.Click ok
3. Selected the CustomerName column. 
Opened the Transform tab.
Selected Format → Capitalize Each Word.
4.Selected the City and State columns.
Selected Merge Columns.
Selected comma as the separator.
Entered Location as the new column name.
5.Selected the Amount column in Order Details.
Selected Data Type → Fixed Decimal Number.
6.if [Amount] = null or [Amount] = 0 or [Profit] = null then null else [Profit] / [Amount]
7.Created conditions based on the Profit column:
If Profit is less than 0 → Loss.
If Profit equals 0 → Break-Even.
Otherwise → Profit.
2.1 Selected the List of Orders query.
Used Merge Queries with the Order Details query.
Selected Order ID as the matching column in both tables.
Selected the appropriate join type.
Expanded the merged Order Details table to include the required columns.
3.1
Selected table.
Selected the identifying column.
Opened Home → Remove Rows → Remove Duplicates.
Q10. How did you sort the Order Data table by Order Date?
Selected the Order Date column.
Opened its filter/dropdown menu.
Selected Sort Descending.
Q11. How did you filter the State column to show Tamil Nadu records?
Selected the State column dropdown.
Cleared Select All.
Selected Tamil Nadu.
Clicked OK.
Part 3: Grouping and Aggregating Data
Q12. How did you calculate the count of each Order ID?
Right-clicked Order Details and selected Duplicate.
Renamed the duplicated query as Order Count Summary.
Selected the Order ID column.
Opened Home → Group By.
Method Used: Group By → Count Rows.
Q13. How did you calculate Average Profit by Category?
Duplicated the Order Details query.
Renamed it as Average Profit by Category.
Selected the Category column.
Opened Home → Group By.
Q14. How did you calculate the total sales target by month?
Duplicated the Sales Target query.
Renamed it as Monthly Sales Target.
Selected the Month of Order Date column.
Opened Home → Group By.
Q15. How did you apply the transformations to Power BI Desktop?
Opened the Home tab in Power Query Editor.
Selected Close & Apply.

