# Car Sales Analysis

## 📌 Project Overview

Car dealership aims to enhance sales performance tracking and analysis for price, sales trends through an efficient Car Sales Dashboard in Power BI. Design and develop interactive Car Sales Dashboard to visualize critical KPIs, enabling data-driven decision-making and understanding sales performance trends

---

## 🎯 Objectives

Design and develop interactive Car Sales Dashboard to visualize critical KPIs, enabling data-driven decision-making and understanding sales performance trends.


 ## 🎯 Data Pre-processing using Excel

Cars.xls

 - if Brand is Empty using find and replace fill the Brand using Model

 - Using find and replace Properly set the improper value Transmission Column.

 - Duplicate Car ID Removed using remove duplicates method

 Sales.xls
 
  - Sale Price Datatype changed

Customer.xls

 - Standardizing Last name Column Using Proper 

 - Concatenate first name and last name and create a new column Name

Sales Overview:

 - Year-to-Date (YTD) Total Sales 

 - Month-to-Date (MTD) Total Sales

 - Growth in Total Sales

 - Difference between YTD Sales and Previous Year-to-Date (PTYD) Sales

Average Price Analysis:

 - YTD Average Price

 - MTD Average Price

 - Growth in Average Price

  - Difference between YTD Average Price and PTYD Average Price

Cars Sold Analysis:

 - YTD Cars Sold
 
 - MTD Cars Sold
 
 - Growth in Cars Sold
 
 - Difference between YTD Cars Sold and PTYD Cars Sold

# Chart Requirements:

 - YTD Sales by Year - Display Bar Chart illustrating the Year for YTD sales. The X-axis should represent Sales, and the Y-axis should show the Year

 - YTD Sales by Color - Present the contribution of various car colours to the YTD total sales through a pie chart.

 - YTD Sales by Model - Visualize the distribution of YTD total sales across different Model using a Donut Chart.

 - YTD Sales by State - YTD sales data based on different City using a map chart to visualize the sales distribution geographically.

 - Model Wise Sales Trend - Tabular grid that displays the sales trend for each car model. The grid should showcase the Model name along with their YTD sales figures.

 - YTD Sales Payment Method: Donut Chart illustrating the method of transaction based on YTD Sales.

 - Using Slicers like brand, transmission, Engine type filtering specific brand, transmission related visualizations for faster decision making.

  - Details Grid Showing All Car Sales Information: Create a detailed grid that presents all relevant information for each car sale, including car model, color,
    sales amount, and customer details

# Data Available
    
Cars Table

 - Car id
 - Brand
 - Model
 - Year
 - Colour
 - Engine Type
 - Transmission
 - Price
 - Quantity in stock
 - Status

Customer Table

 - Customer ID
 - Name
 - Gender 
 - Age
 - Job role
 - Phone
 - Email
 - City
 - State 
 - Region
   
 Sales Table
 
 - Sale id
 - Customer ID
 - Car ID
 - Sales Date
 - Quantity
 - Sale Price
 - Payment Method
 - Salesperson

Calendar Table (Created) (Distinct Sale Date using this table)

 - Date
 - Year
 - Week
   
## Data Modelling
<img width="425" height="475" alt="image" src="Data Modelling .jpg" />

In a star schema, data is split into a central table that holds measurable, quantitative data, surrounded by peripheral tables that hold descriptive attributes.Here is a detailed breakdown of how this model is structured and how the tables interact:

1. Fact Table

Sales is your Fact Table. It sits at the center of the model and records the actual business events (car sales).Foreign Keys contains Car_ID, Customer_ID, and a connection to the Calendar Table (likely via Sale_Date). These keys allow it to connect to the surrounding tables.Measures/Metrics: It holds the numerical values you want to aggregate, indicated by the sigma ($\sum$) icon, such as Quantity and Sale_Price.Attributes: It also tracks transactional details like Payment_Method, Sale_ID, and the Salesperson who made the sale.



   


