#Project: Sales Performance Analysis for a Retail Store
---------------
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Column Description](#column-description)
- [Tools Used](#tools-used)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-(eda))
- [Recommendations](#recommendations)
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
Based on the dashboard image provided, here’s an exploratory data analysis summary, along with recommendations and a conclusion:

### Exploratory Data Analysis (EDA)
1. **Customer Metrics**:
   - **Total Customers**: 9,922 customers have been recorded.
   - **Total Revenue**: The total revenue generated amounts to 2 million.
   - **Total Sales**: There were 68,000 individual sales transactions.
   - **Average Revenue and Sales**: Average revenue per customer is 211.79, while the average sale value is 6.90.

2. **Revenue and Sales by Region**:
   - **Top Revenue-Contributing Region**: The East region is the highest revenue generator, contributing 44.17% of the total revenue.
   - **Regional Sales Distribution**: The distribution shows East leading, followed by West, North, and South, indicating potential differences in demand or marketing effectiveness across regions.
   - **Sales Volume by Region**: North and East are the regions with the highest sales volumes, with North contributing 35.68% and East contributing 42.59% of total sales.

3. **Top and Bottom Performing Products**:
   - **Top 5 Products**: The best-performing products by revenue include Shirts and Shoes, followed by Gloves and Hats.
   - **Bottom 3 Products**: The lower-performing products include Gloves, Jackets, and Socks, with Gloves performing slightly better than the others.

4. **Average Revenue by Product**:
   - Products with higher average revenue include Shirts and Shoes, indicating strong customer preference or higher price points for these items.

5. **Regional Sales Trends**:
   - The sales trend shows a gradual decline from South to West, suggesting a possible geographical disparity in sales performance or a need to boost marketing in lower-performing regions.

![Screenshot (62)](https://github.com/user-attachments/assets/b9e06513-5f7e-4ff7-8046-c47c51b5fb57)


## Recommendations
1. **Targeted Marketing for Low-Performing Regions**:
   - To improve sales in regions like the South and West, consider targeted promotions or localized marketing campaigns. Tailor offers based on regional preferences and market needs.

2. **Focus on Top Products**:
   - Increase inventory and marketing efforts for top-performing products such as Shirts and Shoes. Promoting these items more actively in lower-performing regions might also help boost overall revenue.

3. **Evaluate Product Line for Bottom Performers**:
   - For lower-performing products (Gloves, Jackets, and Socks), consider strategies like discounts or bundling with popular items. Alternatively, assess if these products should be phased out or improved based on customer feedback.

## Conclusion 
---------
The dashboard provides valuable insights into sales performance across products and regions. With the East region and products like Shirts and Shoes leading in revenue, there are clear opportunities for growth by focusing on underperforming regions and products. By strategically targeting marketing efforts, optimizing stock, and enhancing customer engagement, the retail store can drive revenue growth and better meet customer demand across regions.






