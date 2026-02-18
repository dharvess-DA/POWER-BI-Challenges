<img width="1053" height="604" alt="image" src="https://github.com/user-attachments/assets/d1647f0e-4063-4bc8-ac4c-1514a131bd27" />Company: 
Car dealership aims to enhance sales performance tracking and analysis for price, sales trends through an efficient Car Sales Dashboard in Power BI.
Objective
Design and develop interactive Car Sales Dashboard to visualize critical KPIs, enabling data-driven decision-making and understanding sales performance trends.
**Data Pre-processing using Excel**
1.Cars.xls
          ●	if Brand is Empty using find and replace fill the Brand using Model
          ●	Using find and replace Properly set the improper value Transmission Column	
          ●	Duplicate Car ID Removed using remove duplicates method			
2.Sales.xls
          ●	Sale Price Datatype changed
3.Customer.xls
          ●	Standardizing Last name Column Using Proper 
          ●	Concatenate first name and last name and create a new column Name
Sales Overview:
        ●	Year-to-Date (YTD) Total Sales 
        ●	Month-to-Date (MTD) Total Sales
        ●	Growth in Total Sales
        ●	Difference between YTD Sales and Previous Year-to-Date (PTYD) Sales
Average Price Analysis:
        ●	YTD Average Price
        ●	MTD Average Price
        ●	Growth in Average Price
        ●	Difference between YTD Average Price and PTYD Average Price
Cars Sold Analysis:
        ●	YTD Cars Sold
        ●	MTD Cars Sold
        ●	Growth in Cars Sold
        ●	Difference between YTD Cars Sold and PTYD Cars Sold
Chart Requirements:
                1.YTD Sales by Year - Display Bar Chart illustrating the Year for YTD sales. The X-axis should represent Sales, and the Y-axis should show the Year
                2. YTD Sales by Color - Present the contribution of various car colours to the YTD total sales through a pie chart.
                3. YTD Sales by Model - Visualize the distribution of YTD total sales across different Model using a Donut Chart.
                4.YTD Sales by State - YTD sales data based on different City using a map chart to visualize the sales distribution geographically.
                5.Model Wise Sales Trend - Tabular grid that displays the sales trend for each car model. The grid should showcase the Model name along with their YTD sales figures.
                6.YTD Sales Payment Method: Donut Chart illustrating the method of transaction based on YTD Sales.
                7.Using Slicers like brand, transmission, Engine type filtering specific brand, transmission related visualizations for faster decision making.
                8. Details Grid Showing All Car Sales Information: Create a detailed grid that presents all relevant information for each car sale, including car model, color, sales amount, and customer details
**Data Available**
1.Cars Table
    ●	Car id
    ●	Brand
    ●	Model
    ●	Year
    ●	Colour
    ●	Engine Type
    ●	Transmission
    ●	Price
    ●	Quantity in stock
    ●	Status

2.Customer Table
    ●	Customer ID
    ●	Name
    ●	Gender 
    ●	Age
    ●	Job role
    ●	Phone
    ●	Email
    ●	City
    ●	State 
    ●	Region
    ●	Region
 3. Sales Table
●	Sale id
    ●	Customer ID
    ●	Car ID
    ●	Sales Date
    ●	Quantity
    ●	Sale Price
    ●	Payment Method
    ●	Salesperson
Calendar Table (Created) (Distinct Sale Date using this table)
    ●	Date
    ●	Year
    ●	Week

