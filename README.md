
# Bike Company Dashboard Project
## By Alfa Isa Dewa

![My Dashboard Preview](http://url/to/img.png](https://drive.google.com/file/d/10zQE-1Uc7xLiK-CMidU6a1NyUkCf1nyd/view?usp=drive_link)

[View the Dashboard](https://app.powerbi.com/reportEmbed?reportId=be318d78-2a20-4476-9a93-6925e4ad9aef&autoAuth=true&ctid=508916a0-7b89-43a1-af4e-72fe15aba5b9)

## Project Overview

This project involves creating a comprehensive sales dashboard for a global bike company using Power BI. The company specializes in selling bicycles, cycling accessories, and clothing. Operating in multiple countries, the company caters to a diverse customer base, including casual cyclists, professional riders, and enthusiasts. The dashboard is designed to provide insights into key performance metrics such as revenue, profit, orders, transactions, product performance, and customer demographics across various regions.

## Table and Columns
Below is the table and description of the columns in the dataset:

| Column             | Description                                                              |
|--------------------|---------------------------------------------------------------------------|
| `Date`            | The transaction date in YYYY-MM-DD format.                              |
| `Day`             | The day of the transaction date (numeric).                              |
| `Month`           | The transaction month (name of the month).                              |
| `Year`            | The year of the transaction.                                             |
| `Customer_Age`    | The age of the customer at the time of the transaction.                  |
| `Age_Group`       | The age category of the customer (e.g., Youth, Adults).                  |
| `Customer_Gender` | The gender of the customer (M/F).                                        |
| `Country`         | The country where the transaction took place.                            |
| `State`           | The province or region where the transaction took place.                |
| `Product_Category`| The category of the purchased product (e.g., Accessories, Clothing).     |
| `Sub_Category`    | The subcategory of the product within the category.                      |
| `Product`         | The specific name of the purchased product.                              |
| `Order_Quantity`  | The number of products ordered.                                          |
| `Unit_Cost`       | The cost per unit of the product.                                        |
| `Unit_Price`      | The selling price per unit of the product.                               |
| `Profit`          | The profit earned from the transaction.                                  |
| `Cost`            | The total production cost for the transaction.                          |
| `Revenue`         | The total revenue generated from the transaction.                       |

## Structure of the Dashboard

The dashboard consists of three main pages:

1. **Global Performance**

   - Displays overall revenue, profit, number of orders, and transactions.
   - Includes a sales performance trend chart and a breakdown of orders by product categories (Accessories, Clothing, Bikes).
   - Features a detailed order log with data filtered by country.

2. **Country Performance**

   - Highlights total sales, revenue, and profit for a selected country.
   - Includes customer analysis by demographic groups (Adults, Young Adults, Youth, Seniors).
   - Displays a geographical map with sales distribution across states within the selected country.

3. **Product Performance**

   - Shows sales performance for Bikes, Accessories, and Clothing.
   - Includes visualizations for monthly order trends and category-specific product details.

## Tasks Completed

### 1. Data Preparation

- **Data Collection**: Gathered sales, customer, product, and regional past data.
- **Data Cleaning**: Ensured consistent formatting.
- **Data Integration**: Used Power BI’s data transformation capabilities to integrate and model the data.

### 2. Dashboard Design

- **Page Layout**:
  - Global Performance: KPI metrics, trend charts, pie charts, and order logs.
  - Country Performance: State-level maps, demographic charts, and KPI metrics.
  - Product Performance: Gauge charts, bar charts, and product-specific order trends.
- **Wireframe Creation**: Designed the dashboard layout in advance to ensure intuitive navigation.
- **Visualizations**: Selected appropriate visual elements such as maps, line charts, bar charts, and pie charts to enhance readability and usability.

### 3. Dashboard Implementation

- **Development in Power BI**:
  - Created visuals for all KPIs and trends using Power BI’s visualization tools.
  - Added slicers and filters to allow users to explore data by year, country, or product category.
  - Built interactive maps for country and state-level insights.
  - Configured drill-through features for detailed analysis.
- **Data Connection**: Linked the visuals dynamically to the structured data model.

### 4. Deployment and Documentation

- **Deployment**:
  - Published the dashboard to Power BI Service for accessibility across the organization.
- **Documentation**:
  - Provided detailed instructions for dashboard usage, including filtering and drill-through functionality.
  - Documented the data model, including table relationships and calculated measures.

## Instructions for Use

1. Open the Power BI dashboard using the shared link in Power BI Service.
2. Navigate through the three pages using the tabs at the bottom.
3. Use the slicers and filters to explore specific data, such as:
   - Filtering by year or country.
   - Drilling down into specific product categories or customer demographics.
4. For detailed analysis, use the drill-through feature by right-clicking on a data point.
5. Export reports if needed using the “Export” option in Power BI Service.

## Tools and Technologies Used

- **Power BI Desktop**: For creating the dashboard.
- **Power BI Service**: For publishing and sharing the dashboard.

---
