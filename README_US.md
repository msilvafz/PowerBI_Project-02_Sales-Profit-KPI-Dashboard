# 📊 Sales, Cost, Profit & KPI Dashboard  

Dashboard developed in **Microsoft Power BI**, focused on **analyzing sales, costs, profits, and performance indicators (KPIs)**.  

> 💡 This project presents the full process — from **data extraction and modeling (ETL)** to **DAX metrics creation** and **interactive visualizations** for business insights.

---

## 📢 Overview  

This project demonstrates the practical use of **Power BI** in building **executive and analytical dashboards**, applying best practices in **data modeling, DAX, and visual design**.  
The layout was designed with a focus on **clarity, performance, and storytelling**, prioritizing metrics that support **strategic decision-making**.

---

## 🎯 Objective  

Analyze business performance through key indicators, identifying:  
- **Profit margin trends** over time.  
- **Average shipping costs** by market.  
- **Profit distribution** among product categories.  
- **Sales volume variations** by shipping mode.  
- **Sales goal achievement (KPI)**.  

---

## ⚙️ Process Overview  

* 📥 **Data integration**: importing multiple sources — *customers, orders, products, and sales*.  
* 🧹 **Data cleaning and transformation** in Power Query:  
  - Removed duplicates and unnecessary columns.  
  - Adjusted data types and relationships.  
* 🧩 **Data modeling** with various cardinalities (*1:1*, *1:N*, *N:N*).  
* 🧮 **DAX measures created**:  
  - `Profit = Sales Value - Shipping Cost`  
  - `Profit Margin = DIVIDE(Profit, Sales Value)`  
* 🧠 **Additional functions**: `ROUND()` and `DIVIDE()` for precise calculations.  
* 🎯 **KPI setup** to track sales performance goals (target: R$350).  
* 🎨 **Customized design** with dark theme, icons, and visual hierarchy.  

---

## 📊 Visualizations Used  

Each chart was chosen strategically to answer specific business questions and enhance data interpretation:

- **📈 Profit Margin Trend Over Time**  
  → Line chart used to display profit margin evolution from 2011 to 2014, showing stability and fluctuations over the years.  

- **💰 Average Sales Value (KPI)**  
  → KPI gauge indicator set with a target of R$350, allowing quick tracking of whether average sales meet the goal.  

- **🌍 Average Shipping Cost by Market (Treemap)**  
  → Treemap visualization comparing average shipping costs across global markets, highlighting regions with higher logistics expenses.  

- **🏷️ Average Profit by Product Category (Donut Chart)**  
  → Donut chart showing the share of each product category (Technology, Furniture, and Office Supplies) in total average profit.  

- **🚚 Sales by Shipping Mode (Waterfall Chart)**  
  → Waterfall chart showing how each shipping mode contributes to total sales, highlighting positive and negative impacts.  

---

## 💡 Key Insights  

- 🚚 **“Standard Class” shipping mode** had the highest total sales value.  
- 🌎 The **APAC market** had the highest average shipping cost.  
- 💰 The **Technology category** achieved the highest average profit.  
- 📉 The **average sales value** remained **below the target of 350**, according to the KPI.  
- 📊 The **profit margin remained stable** throughout the analyzed period, with slight yearly variations.  

---

## 🧠 What I Learned  

- Applied the **ETL process (Extract, Transform, Load)** using Power Query for data cleaning and modeling.  
- Built **table relationships** ensuring data integrity and consistency.  
- Developed **custom DAX columns and measures**.  
- Configured **KPI indicators** for sales goal tracking.  
- Improved knowledge of **advanced DAX functions** and formatting best practices.  
- Fully customized the dashboard design, focusing on clarity and executive-level impact.  

---

## 🧰 Tech Stack  

* 💻 **Microsoft Power BI Desktop**  
* ⚙️ **Power Query**  
* 🧮 **DAX (Data Analysis Expressions)**  

---

## 🗂️ Project Structure  

- 📁 **/data** → Contains the CSV files used in the analysis.  
- 📁 **/dashboard** → Main Power BI file (`.pbix`) containing all modeling and visualizations.  
- 📁 **/images** → Screenshots of the final dashboard.  

---
