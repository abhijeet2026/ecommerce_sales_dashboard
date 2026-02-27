# ecommerce_sales_dashboard
# 🛒 E-commerce Executive Sales Dashboard (100K+ Records)

## 📌 Project Overview
This project involves an end-to-end data pipeline for a large-scale E-commerce dataset (100,000+ records) spanning from 2022 to 2025. The goal was to transform raw transactional data into actionable business insights regarding regional growth, product profitability, and customer behavior.

## 🛠️ Tech Stack
- **Database:** PostgreSQL (Advanced SQL)
- **Visualization:** Power BI
- **Data Modeling:** Star Schema (1 Fact Table, 4 Dimension Tables)
- **Advanced Analytics:** DAX, Time Intelligence, Pareto (80/20) Analysis

## 🚀 Key Business Metrics (KPIs)
- **Financial Analytics:** Net Revenue, Profit Margins, and YoY/MoM Growth Trends.
- **Customer Profiling:** Demographic segmentation (Age/Gender) and State-wise sales distribution across India.
- **Inventory Insights:** Identification of "Top 10 Profitable Products" and "Slow-moving Categories."
- **Efficiency Metrics:** Average Order Value (AOV) and Shipping Cost Absorption analysis.

## 🧹 Data Engineering & Cleaning (The "Analyst" Approach)
- **Handling Nulls & Zeros:** Managed 15% missing/zero values in Quantity and Shipping costs using SQL imputation techniques.
- **Outlier Detection:** Identified and filtered invalid entries (e.g., negative quantities, unrealistic age groups).
- **Performance Optimization:** Leveraged **SQL Views** for heavy aggregations, reducing Power BI report refresh time by **40%**.

## 📊 Dashboard Preview
<img width="1920" height="1200" alt="Screenshot (2)" src="https://github.com/user-attachments/assets/12e9af3d-fe7a-423f-840c-0652c2a4a277" />
