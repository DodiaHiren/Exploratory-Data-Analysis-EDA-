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

### SQL Queries
![Image](https://github.com/user-attachments/assets/8b3c4093-e2df-45cf-ad3b-c114b29bfcf1)

![Image](https://github.com/user-attachments/assets/7ef380e2-b5d2-4c9c-86fe-2c9e2e9c42a3)

![Image](https://github.com/user-attachments/assets/695421ea-0176-44c2-90ec-bc2817ab282d)

![Image](https://github.com/user-attachments/assets/30edc104-7252-4e5b-b569-45c93376c3d8)

![Image](https://github.com/user-attachments/assets/3d6f79ad-30d7-4820-b541-b1754db779c4)

![Image](https://github.com/user-attachments/assets/c3492d06-793d-4a89-8320-c98f8bb92b36)

![Image](https://github.com/user-attachments/assets/5875d565-c9ac-4e06-9365-61508e58cb6d)

![Image](https://github.com/user-attachments/assets/a688e6b8-ae8e-4620-a73b-9655270ae9fb)

### Visualization using Power BI
![Image](https://github.com/user-attachments/assets/c486100c-0a55-4b46-a7fb-fc9a1feb46b4)

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
