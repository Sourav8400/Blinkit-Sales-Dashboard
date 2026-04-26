# Blinkit-Sales-Dashboard
# 🛒 Blinkit Data Analysis Project using Excel, SQL & Power BI  

## 📌 Recommended Structure and Order  

## 1. Project Overview  
This project delivers an end-to-end analytical assessment of retail sales data from [Blinkit](https://blinkit.com), with a focus on uncovering actionable insights related to product performance, outlet efficiency, and consumer purchasing behavior.

The objective is to leverage data cleaning techniques, SQL-based analytical querying, and advanced Power BI visualizations to support strategic, data-driven decision-making in the quick-commerce ecosystem.  

---

## 2. Tech Stack  
- Power BI: Interactive dashboard development and data storytelling  
- MySQL / SQL: Data extraction, transformation, and complex query optimization  
- MS Excel / CSV: Data preprocessing, validation, and structuring  
- Power Query: Data transformation, data modeling, and ETL operations

---

## 3. Data Source  
The dataset consists of structured retail sales records across multiple outlets of [Blinkit](https://blinkit.com).  

**Key attributes include:**  
- Product-level data: Item Identifier, Category, Fat Content, Item Weight  
- Transactional metrics: Total Sales, Average Sales, Item Visibility  
- Outlet characteristics: Outlet ID, Size, Tier-based Location (Tier 1, 2, 3), Outlet Type  
- Performance indicators: Customer ratings and product-level KPIs  

---

## 4. Key Features / Highlights  
- Executed comprehensive data cleaning and transformation to ensure high data quality and consistency  
- Designed and optimized SQL queries to analyze sales distribution, outlet performance, and product segmentation  
- Developed a dynamic and interactive Power BI dashboard incorporating:  
- Key Performance Indicators (KPIs): Total Sales, Average Sales, Total Items, Average Rating  
- Category-wise revenue contribution and trend analysis
- Product segmentation based on fat content (Low Fat vs Regular)
- Outlet performance analysis by size and geographic tier
- Temporal analysis of outlet establishment and growth trends 
- Enabled identification of high-performing categories, customer preferences, and operational bottlenecks  

---

## 5. Example SQL Queries  
```sql
-- Revenue contribution by product category
SELECT Item_Type, SUM(Total_Sales) AS total_revenue
FROM blinkit_data
GROUP BY Item_Type;

-- Performance comparison across outlet sizes
SELECT Outlet_Size, AVG(Total_Sales) AS avg_revenue
FROM blinkit_data
GROUP BY Outlet_Size;

-- Product segmentation by fat content
SELECT Item_Fat_Content, COUNT(*) AS product_count
FROM blinkit_data
GROUP BY Item_Fat_Content;
```

## 6. Power BI Dashboard Insights
- Achieved total revenue exceeding $1.2M across all outlets, indicating strong overall performance
- Identified top-performing categories including Fruits, Snacks, and Household products contributing significantly to revenue
- Observed higher sales volume for Regular fat products compared to Low Fat variants, indicating consumer preference trends
- Determined that Tier 3 outlets contribute the highest share of total sales, highlighting regional demand patterns
- Found that medium-sized outlets consistently outperform small and large outlets in terms of revenue generation

## 7. Power BI Dashboard Preview
<img width="1256" height="729" alt="Home Page" src="https://github.com/user-attachments/assets/4b49c12e-9f19-4159-9694-3f5f41b35b81" />
<img width="1127" height="674" alt="Snapshot of the Dashboard" src="https://github.com/user-attachments/assets/7b3f7cf2-16a6-4549-b556-c109317ba329" />
<img width="1108" height="665" alt="Table Data" src="https://github.com/user-attachments/assets/0a7b7294-efb5-416d-8417-f9af777a4bb9" />

## Conclusion
This project demonstrates a complete data analytics lifecycle, including data preprocessing, SQL-driven exploratory and analytical processes, and interactive visualization using Power BI.

The insights derived provide a strong foundation for optimizing product strategy, improving outlet-level performance, and enhancing customer satisfaction for organizations such as [Blinkit](https://blinkit.com).
