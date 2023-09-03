# Maven-Market

This is a Power BI file where I created a dashboard for the Maven-Market Bonus Project from Udemy.
Firstly, I took the data into Excel and transformed it into a Power BI query Editor where I made changes accordingly.
There are various tables in this dataset. 
For Example: 
1) Changing the date format
2) Adding a new column as the full name for the first_name and last_name in the customer's table.
3) Extracting their birth year from their birthdate using Delimiter in the customer's table.
4) I have added a new column as discounted price using the custom column in the products table.
5) I have merged the column of store city, state, and country into one column as address while using space as a separator in the store's table.
6) I have used date functions in the Calendar table and added various columns like the start of the week, the start of the month, the Day name, and the Year.
7) I have removed the unwanted columns from the transaction data table.

Then in Model view, I made a relationship between tables from scratch by keeping all the dimension(lookup) tables up and facts(data) tables down. Connecting them through Primary keys and Foreign keys while the stores and region table made Snowflake Schema. Keeping all the filters in a single direction and hiding all other fields that are not used from the report view.

Then in the Table view, I corrected the format of the date as short date because here the report will be seen by another employer or manager where it should be easily readable for others to view and check data.

I also created some measures using DAX such as All transactions, Quantity Sold, Total Cost, Total Profit, Total Revenue, Last Month's transaction, LAst month's profit, Quantity Returned, etc

Then Into the report view, the first I did was add an image of Maven Market given with resources of files.
1) The first thing I added was a Matrix with different columns to view accordingly and  I also added conditional formatting there to know the most transactional product and which product brand has the high profit margin etc.
2) Then I created three KPI Cards that show the current month's transactions, the current Month's profit, and the current month's returns. There are the measures that I created to use in the report using DAX.
3) Then below the cards I made the basic Map chart with the given slicer of countries.
4) Next to it is a Tree Chart of countries which uses the drill up and down options while having countries, states, and cities drill down.
5) A stacked Column Chart for weekly trending revenue and a gauge chart that shows the revenue versus target.

I have edited the interactions of the Matrix with the tree chart as well to stop filtering the tree chart whenever something is selected from the matrix.

I created another page called Notes which has the bookmarks of my finding. 
