# superstore-data-analysis
Made use of superstore data to perform below tasks
Load the data into power BI & perform below transformations.
A) Clean the Order Priority column, example- 1-Critical  Critical etc. 
B) Calculate column for no of days taken to ship the product.
C) Create cost bucket based on Sales column
a. Sales <=0 then “Very Low”
b. Sales > 0 & Sales <=300 then “Low”
c. Sales > 300 & Sales <=1000 then “Medium”
d. Sales > 1000 & Sales <=5000 then “High”
e. Sales > 5000 then “High”

2. Calculate master calendar (2010 to 2025) in power bi file (Date, Year, Month, Quarter, Day, Quarter-Year, 
Month-Year)

3. Create measure for total sales for west region.

4. Add below Slicers on the “Summary” Page of the report.
a. Order Date (In Range format)
b. Customer Segment (Dropdown)
c. Product Category (Dropdown)
d. Product Sub Category (Dropdown)
e. State (Dropdown)
f. City (Dropdown)

5. Create below visuals to showcase analysis & do formatting as per your choice.
a. Sales by Order date (Line chart) Note - Please exclude June month data from visual
b. Profit by Customer segment (Pie Chart)
c. Average Discount by Product Container (Column Chart)
d. Create table matrix with Category, Customer Segment, Total Sales, Sales %.

6. Customer segment slicer should not filter visual where customer segment column is used. (Hint- Use edit 
interaction)

7. Create Detail page with Order date, Category, Sub Category, Customer segment, Customer Name, Profit, Sales

8. Sync the slicers on the “Details” Page.

9. Add Page Navigation from “Summary Page” to “Details” page & vice versa.

10. Add drill through functionality for visual 5(b) i.e., Customer segment.
