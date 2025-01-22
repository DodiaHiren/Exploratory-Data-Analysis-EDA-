# Exploratory-Data-Analysis

### Sales - MySQL Analysis

### Project Overview
***Objective***:
- Analyze customer behavior, sales trends, and product performance

***Datasets***:
- Category
- Order_Details
- Orders
- Users

### Database Design
**Schema Definition**

***Category***: CategoryID, CategoryName, Description

***Order_Details***: OrderDetailID, OrderID, ProductID, Quantity, UnitPrice, Total

***Orders***: OrderID, UserID, OrderDate, OrderStatus

***Users***: UserID, UserName, Email, RegistrationDate, Location

***Relationships***: Foreign keys link Orders to Users and Order_Details.

### Data Exploration -Key Questions
1. **Sales Performance**:
- Total sales by category and product.
2. **Customer Insights**:
- Active locations and top buyers.
3. **Operational Insights**:
- Order status breakdown and trends.

### Visualization using Power BI


### Insights
1. Total Sales by Category: Identifies which categories generate the most revenue.
2. Monthly Sales Trends: Shows sales trends over time, highlighting any seasonal patterns.
3. Top 5 Users by Spending: Recognizes the top 5 users who have spent the most money.
4. Monthly Revenue for 2019: Analyzes financial performance month by month for 2019.
5. Category with Highest Average Profit per Order: Identifies the most profitable category.
6. Monthly Order Count for 2019: Understands order volume trends throughout 2019.
7. User with Most Diverse Orders: Recognizes users with diverse purchasing habits.
8. Total Profit by User and Profit Group: Segments users based on their profitability.
9. Top 3 Cities by Average Order Amount: Identifies the most lucrative markets.
