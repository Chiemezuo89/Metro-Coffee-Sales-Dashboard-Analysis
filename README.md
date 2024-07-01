# Metro Coffee Sales Dashboard Analysis

## Problem Statement
Metro Coffee aims to understand its sales performance better to inform strategic decision-making and growth initiatives. A comprehensive analysis and visualization using Excel are required to provide insights into customer behavior, market performance, and potential areas for improvement.
The task to provides a clear visualization of our performance metrics using Excel to create an interactive and comprehensive view of our sales data, highlighting key areas and trends.
The dashboard's country-specific revenue breakdown will help understand the market distribution and plan strategic initiatives accordingly.

## Objective
To create an interactive and comprehensive sales dashboard in Excel that visualizes key performance metrics and the revenue distribution by country, enabling Metro Coffee to make data-driven decisions to enhance sales strategies and market outreach.

### Steps followed 

- Step 1 : Load data into MS Excel, dataset is a csv file.

- Step 2 : Using the XLOOKUP function, columns like Customer Name, Email, Country,Coffee typem Roast Type, size, etc was joined from customer table and product table to the order table
- Step 3 : Checked for blanks in the new table and corrected each column to the right data type.
- Step 4 : The Email was having blank rows, a condition function "=IF(XLOOKUP([@[Customer ID]],Table2[Customer ID],Table2[Email])=0,"",(XLOOKUP([@[Customer ID]],Table2[Customer ID],Table2[Email])))" was usd to correct it
- Step 5 : Total sales column was created by multipying quantity and unit price.
- Step 6 : Coffee type and Roast type was renamed in full because it came with an abbreviation in the data set.
- Step 7 : The new table was loaded to power query where REVENUE BY COUNTRY, TOP 5 CUSTOMERS,TOTAL REVENUE, ETC
- Step 8 : A visualizations was assigned to each of the query from the insert view pane
- Step 9 : Proceeded in creating a sales report dashboard, a bar charts was was added to the canvas deplicating REVENUE BY COUNTRY, TOP 5 CUSTOMERS, SALES YEAR TREND.
- Step 10 : A slicer was added covering LOYALTY CARD, COFFEE TYPE, COFFEE SIZE AND COUNTRY effecting the dasboard.
- Step 11 : Lastly, a timeline (order Date) to the dashboard.

### Quick breakdown

- Total Customers: 913 distinct customers
- Total Orders: 1000 orders placed
- Total Revenue: $45,134 generated


### Revenue Breakdown by Country
- United Kingdom: $35,639
- Ireland: $6,697
- United States: $2,799


### Key Takeaways:
- Our loyal customer base is growing steadily with 913 distinct customers.
- We've hit the milestone of 1000 total orders, showcasing strong demand.
- Our total revenue stands at an impressive $45,000.
- The United Kingdom is our leading market, contributing $36,000 to our total revenue.
