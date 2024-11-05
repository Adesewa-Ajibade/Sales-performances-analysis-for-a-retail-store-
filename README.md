#Project: Sales Performance Analysis for a Retail Store
---------------
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Column Description](#column-description)
- [Tools Used](#tools-used)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-(eda))
- [Conclusion](#conclusion)

  
## Project Overview 
---------
This project involves analyzing the sales performance of a retail store to derive actionable insights such as top-selling products,
regional performance, and monthly sales trends. 


## Data sources 
---------
The dataset for this analysis was provided by Ladies in Tech Africa (LITA )_Incubator Hub , an organization for learning and training purposes. The data was provided in xlsx format, [download here](https://canvas.instructure.com/files/273182802/download?download_frd=1)making it accessible for analysis
## Column Description
---------
* OrderID: A unique identifier for each order.
* CustomerId: A unique identifier for each customer placing an order.
* Product: The specific product purchased in each transaction.
* Region: The geographical location (e.g., North, South, East, West) where the order was placed.
* OrderDate: The date when the order was made.
* Quantity: The number of units purchased for each product in an order.
* UnitPrice: The price per unit of the product.
* Total Sales: The total sales value for the order, calculated as Quantity * UnitPrice
## Tools Used 
---------
* [Microsoft Excel](www.microsoft.com)-Data Cleaning, Data Analysis 
* [Microsoft SQL](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) ;[SSMS](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16)- Data Querying 
* [Microsoft PowerBI](https://www.microsoft.com/en-us/download/details.aspx?id=58494)- Data Visualization 
## Exploratory Data Analysis (EDA)
 ---------
Data cleaning and Preparation Insights from Excel
---------
Excel served as the primary tool for initial data preparation, addressing missing spaces and removing duplicates to ensure data accuracy. Key metrics were calculated using functions such as SUMIF and AVERAGEIF, offering insights into average sales per product and total revenue by region.


 ![Screenshot (57)](https://github.com/user-attachments/assets/90403582-cc01-489d-b3c9-19a88751797c)

Pivot tables provided an in-depth analysis to:

- Summarize total sales by product, region, and month
- Identify high-revenue products
- Observe monthly and average sales trends
- Highlight underperforming products within each region


![Screenshot (55)](https://github.com/user-attachments/assets/90b816b2-4fd1-45e3-90b6-e64a7a56e3b5)

![Screenshot (56)](https://github.com/user-attachments/assets/6a0f5789-008b-4cf4-9a0b-107493a7acf4)


Excel enabled efficient data exploration and contributed to a comprehensive view of sales performance, facilitating data-driven insights.

### Data Querying insight 
---------
SQL enabled a more advanced analysis of the data, adding depth to the insights gathered in Excel.

- **Revenue by Product Category**: SQL queries delivered detailed revenue insights by product category, supporting strategic product planning.
- **Top-Selling Products and Key Accounts**: SQL identified products with the highest sales and highlighted top customers by total purchases, helping prioritize key accounts and resource allocation.
- **Quarterly Sales and Low-Selling Products**: SQL analysis revealed quarterly sales trends and identified products with no sales, informing product lineup adjustments. 


![Screenshot (51)](https://github.com/user-attachments/assets/e90393f9-8c82-439b-bee4-7d8fa1d28d0b)

![Screenshot (52)](https://github.com/user-attachments/assets/cda1ea5d-0b6d-47aa-a5ef-a929d764acf0)

![Screenshot (53)](https://github.com/user-attachments/assets/c6889c29-46ae-452c-ba96-45fe3af90c27)


Overall, SQL contributed specific, actionable insights to enhance decision-making and optimize sales strategies..

### Data Visualization  from Power BI
---------

*Comprehensive Sales Overview:Key metrics and top-selling products were visualized, providing stakeholders with a high-level view.
*Interactive Regional Sales Analysis:An interactive regional sales breakdown allowed exploration of performance differences across regions.
*Seasonal and Monthly Sales Patterns: Monthly sales trends and seasonality insights supported planning for peak periods.
*Deep-Dive Views for Top Customers and Products: Drill-down capabilities in Power BI enabled detailed views into high-value customers and products, enhancing targeted decision-making.



## Conclusion 
---------

The sales data analysis gave useful information on trends, product performance, and sales in different regions. Key findings show how important it is to understand changes in sales over time, 
manage inventory well, and use targeted marketing. By noticing seasonal trends and identifying top products and customer groups, the company can make smart decisions to improve sales. 
In summary, this project shows the potential for growth through informed choices. By responding strategically to trends and patterns, 
the company is set to boost sales, improve profits, and achieve steady growth in the years ahead.







