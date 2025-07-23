📦 Blinkit Analysis Dashboard
------------------
**Overview:**
Built an all-in-one Power BI dashboard analyzing Blinkit's business data, focusing on sales, delivery times, product categories, customer behavior, and revenue trends. The dashboard enables real-time tracking of KPIs and operational performance across multiple categories and locations.

**Objective**
To analyze Blinkit’s delivery and sales performance through a unified dashboard, aiding strategic decisions in fast-paced, hyperlocal delivery markets.

**Tools & Technologies**
Power BI
Power Query
DAX
Excel (source dataset)

**📁 Dataset Details**
Product Orders, Categories, Customer Info

Metrics: Order Value, Delivery Time, Product Count, Discounts, Profit, Region

Format: .csv/.xlsx files

📈 Data Analysis Steps (Power BI)
-----------------------------
**Data Loading**

Imported order and product data into Power BI from multiple .csv files.

Merged tables using Power Query for unified modeling.

**Data Cleaning**

Removed nulls, fixed column types (currency, datetime), filtered out test data.

Created lookup tables: City, Product Category, Delivery Zone.

**Data Modeling**

Established relationships across orders, products, customer profiles, and geography.

Created Date Table for time-based slicing.

**DAX Measures Created**

Total Orders, Total Revenue, Avg Delivery Time, Profit Margin, Repeat Customers %, Average Basket Size

**Dashboard Visuals**

KPIs Cards: Revenue, Profit, Orders, Avg Delivery

Line Charts: Sales Trends over Time

Bar Charts: Revenue by Product Category & City

Pie Chart: Customer Repeat Rate

Matrix: Order status by day/time

Filters and Slicers

By City, Date, Product Category, and Delivery Status

**Key Insights**

High revenue generated from 3 major cities

Groceries contributed 35% of sales volume

Avg delivery time: 14.2 mins, with spikes on weekends

25% orders placed during 6–9 PM peak window

Repeat customers accounted for 42% of revenue

🎯 Business Insights
-----------
Blinkit's delivery performance aligns with customer peaks; real-time dashboards help prioritize zip codes for optimization.

Seasonal category trends help in targeted marketing.

Inventory planning improved using category-wise and city-wise data breakdown.

Screenshot
----------

![Main Dashboard](https://github.com/user-attachments/assets/0f5c5a10-f0c0-4bb1-af32-5a908a9bcab3)

| File                                          | Description                     |
| --------------------------------------------- | ------------------------------- |
| `blinkit_dashboard.pbix`                      | Interactive Power BI dashboard  |
| `orders.csv`, `products.csv`, `customers.csv` | Raw data                        |
| `README.md`                                   | GitHub documentation            |
| `slides.pptx`                                 | Summary slides for stakeholders |

## Author
Malini Roy Choudhury - Data Analyst | Freelancer
