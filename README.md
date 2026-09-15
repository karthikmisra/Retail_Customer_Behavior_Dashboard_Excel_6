# Retail_Customer_Behavior_Dashboard_Excel_6
An executive-level data analytics and business intelligence project evaluating customer purchasing patterns, demographics, product preferences, and Customer Lifetime Value (CLV) using advanced Excel modeling and visualization techniques.
# 📊 Retail Customer Behavior & Lifetime Value (CLV) Analytics Dashboard

## 🎯 Project Overview
This project analyzes comprehensive customer records (`Retail Company Record.xlsx`), merging demographic profiles with transactional purchase logs (spanning across ages, income brackets, education levels, and recency intervals). The objective is to uncover key revenue drivers and provide actionable marketing strategies for customer retention.

### Key Business Questions Addressed:
1. **Age Group Purchasing Behavior:** Analyzed total purchasing volume across age segments, revealing that customers aged **>50** drive the vast majority of transactions (~72% of total volume).
2. **Product Category Popularity:** Compared fruit vs. sweet product sales, identifying **Sweet Products** as the top category ($60.6K / 50.7% share).
3. **Income vs. Customer Lifetime Value (CLV):** Uncovered a strong positive correlation ($\approx 0.53$) between customer income and purchase frequency, with upper-middle income brackets ($50K–$100K) acting as the primary volume engine.
4. **Education & Engagement Patterns:** Evaluated how educational background influences purchasing volume, showing strong individual engagement among PhD and Graduate tiers.
5. **Customer Recency & Churn Risk:** Mapped average recency periods via a heatmap across marital status and education levels to flag dormant segments (such as Widows with Basic education).

## 🚀 Dashboard Features & Components
* **Dynamic KPI Summary Cards:** Live calculations tracking total revenue, purchase volume, average customer income, and recency metrics.
* **Interactive Visualizations:**
  1. *Total Purchases by Age Group* (Column Chart)
  2. *Product Category Sales Share* (Pie Chart)
  3. *Income vs. Purchases Correlation* (Scatter Plot / Trend Analysis)
  4. *Education & Marital Status Recency* (Heatmap Matrix)
* **Master Slicers:** Connected interactive filter controls allowing users to dynamically filter all underlying pivot tables and metrics simultaneously by education and marital status.

## 📁 Dataset Source & Files
* **Dataset Name:** `Retail Company Record.xlsx` (Contains `customer_dataset` and `purchase_dataset` sheets).
* **Data Source Link:** https://github.com/karthikmisra/Retail_Customer_Behavior_Dashboard_Excel_6/blob/main/Retail_Customer_Behaviour_Dashboard_Excel_6.xlsx
* **Key Metrics Analyzed:** `Year_Birth`, `Income`, `NumWebPurchases`, `NumStorePurchases`, `MntFruits`, `MntSweetProducts`, `Dt_Customer`, `Recency`, `Education`, `Marital_Status`.

### 1. Dashboard Layout & Analysis View
https://github.com/karthikmisra/Retail_Customer_Behavior_Dashboard_Excel_6/blob/main/Screenshot%20of%20the%20Dashboard.png

## ⚙️ How to Use This Repository
1. Download the `Retail Company Record.xlsx` file.
2. Open the file in Microsoft Excel and ensure your customer and purchase sheets are joined by customer `ID`.
3. Utilize the calculated helper columns (`Total_Purchases`, `Age_Group`, `Income_Group`, `Lifespan`) to explore pivot tables and interactive slicers.

---
*Created with passion for Retail Analytics & Business Intelligence.*
