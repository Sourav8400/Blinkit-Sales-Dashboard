# Blinkit-Sales-Dashboard
# 🛒 Blinkit Data Analysis Project using Excel, SQL & Power BI  

## 📌 Recommended Structure and Order  

## 1. Project Overview  
This project presents a comprehensive analysis of retail sales data from Blinkit, aimed at deriving actionable insights into product performance, outlet efficiency, and customer purchasing behavior.  

The primary objective is to perform data cleaning, execute SQL-based analytical queries, and develop interactive Power BI dashboards to enable data-driven decision-making within the quick-commerce domain.  

---

## 2. Tech Stack  
- Power BI: Advanced data visualization and dashboard development  
- MySQL / SQL: Data extraction, transformation, and analytical querying  
- MS Excel / CSV: Data preprocessing and dataset management  
- Power Query: Data transformation and modeling  

---

## 3. Data Source  
The dataset comprises structured retail sales data across multiple Blinkit outlets.  

**Key attributes include:**  
- Item-level data: Item Identifier, Item Type, Fat Content, Item Weight  
- Sales metrics: Total Sales, Average Sales, Item Visibility  
- Outlet details: Outlet Identifier, Size, Location Type (Tier 1, 2, 3), Outlet Type  
- Performance indicators: Customer ratings and product-level metrics  

---

## 4. Key Features / Highlights  
- Performed data cleaning and transformation to ensure data consistency and reliability  
- Designed and executed SQL queries to evaluate sales trends and operational performance  
- Developed an interactive Power BI dashboard incorporating:  
  - Sales KPIs (Total Sales, Average Sales, Number of Items, Average Rating)  
  - Category-wise sales distribution  
  - Fat content-based product segmentation  
  - Outlet size and location performance analysis  
  - Year-wise outlet establishment trends  

- Delivered insights into demand patterns, category performance, and outlet efficiency  

---

## 5. Example SQL Queries  
```sql
-- Total sales by item category
SELECT Item_Type, SUM(Total_Sales) AS total_sales
FROM blinkit_data
GROUP BY Item_Type;

-- Average sales by outlet size
SELECT Outlet_Size, AVG(Total_Sales) AS avg_sales
FROM blinkit_data
GROUP BY Outlet_Size;

-- Distribution of items by fat content
SELECT Item_Fat_Content, COUNT(*) AS total_items
FROM blinkit_data
GROUP BY Item_Fat_Content;
```

## 6. Power BI Dashboard Insights
- Sales Performance: Achieved total revenue exceeding $1.2M across all outlets
- Product Analysis: High contribution from categories such as Fruits, Snacks, and Household goods
- Customer Preference: Regular fat products demonstrated higher sales compared to low-fat alternatives
- Geographic Insights: Tier 3 locations contributed significantly to overall revenue
- Operational Efficiency: Medium-sized outlets outperformed other outlet categories

## 7. Power BI Dashboard Preview
<img width="1256" height="729" alt="Home Page" src="https://github.com/user-attachments/assets/4b49c12e-9f19-4159-9694-3f5f41b35b81" />
<img width="1127" height="674" alt="Snapshot of the Dashboard" src="https://github.com/user-attachments/assets/7b3f7cf2-16a6-4549-b556-c109317ba329" />
<img width="1108" height="665" alt="Table Data" src="https://github.com/user-attachments/assets/0a7b7294-efb5-416d-8417-f9af777a4bb9" />

