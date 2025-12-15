# Exploratory Data Analysis (EDA) – Retail Sales (Superstore Dataset)

## 1. Project Objective
The objective of this project is to analyze retail sales data from a real-world Superstore dataset to uncover trends, understand customer behavior, evaluate product performance, and provide actionable business recommendations.

---

## 2. Dataset Overview
- **Dataset:** Superstore Retail Sales  
- **Number of records:** 500+  
- **Number of features:** 9  
- **Time period:** 2018 – 2019  
- **Key columns:** Order Date, Order ID, Customer ID, Product Category, Product Name, Quantity, Sales, Region, Payment Method

---

## 3. Data Cleaning Summary
- Missing values were identified and addressed.  
- Duplicate records were removed.  
- `Order Date` column converted to datetime format with proper handling of mixed date formats.  
- Invalid dates were dropped to ensure accurate time-series analysis.  
- Correct data types were enforced for numerical and categorical columns.

---

## 4. Key Insights

### Sales Trends
- Monthly sales show **seasonal patterns** with peaks during specific months.  
- Overall sales trend shows **gradual growth**, indicating positive business performance.

### Product Analysis
- **Electronics and Furniture** categories generate the highest revenue.  
- Some product sub-categories show **consistently low performance**, suggesting areas for improvement or promotion.

### Customer Analysis
- A **small percentage of customers** contribute to a large portion of total sales (high-value customers).  
- Repeat customers are important for **consistent revenue**.

### Regional Performance
- **West** and **East** regions lead in total sales.  
- Some regions show **underperformance**, indicating potential for targeted marketing or expansion.

### Visualization Highlights
- **Line charts**: Monthly sales trend over time.  
- **Bar charts**: Total sales by product category and region.  
- **Heatmap**: Sales distribution across regions and product categories.

---

## 5. Business Recommendations
- Prioritize **high-performing categories** for promotions and expansion.  
- Improve supply chain and inventory in **underperforming regions**.  
- Offer **loyalty programs** to top customers to maintain retention.  
- Analyze **low-performing products** for discontinuation, bundling, or promotional campaigns.  
- Plan inventory and marketing strategies around **seasonal peaks** identified in monthly trends.

---

## 6. Conclusion
The EDA revealed actionable insights on sales trends, customer behavior, and product performance. These insights can guide **data-driven decision-making** and improve overall business strategy for the retail store.

---

## 7. Optional Figures (if added)
- `figures/monthly_sales.png` – Monthly sales trend  
- `figures/category_sales.png` – Sales by product category  
- `figures/heatmap_region_category.png` – Heatmap: Region vs Category sales
