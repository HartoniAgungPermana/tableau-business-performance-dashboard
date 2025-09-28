# 📊 **Tableau Business Performance Dashboard — Portfolio Project**

<p align="center">
  <img src="resources/Dashboard Demo.gif" alt="Business Performance Dashboard Demo" />
</p>

This project is a **Tableau-based interactive dashboard** designed for a fictional retail company, **FlipMart**. Leveraging **Tableau’s advanced data visualization and interactivity** to generate deeper business insights.  

The dashboard provides a **dual view**:  
- 🛒 **Sales Performance Page** — focuses on sales, profit, and product categories.  
- 👥 **Customer Performance Page** — focuses on customer loyalty, growth, and top contributors.  

Users can **switch between Sales and Customer views** via a navigation button, while still analyzing the same business data. The dashboard was built to simulate a **real-world BI workflow**, where executives can toggle perspectives without leaving the dashboard.

## 🎯 **Business Objectives**

The project was designed to help stakeholders:  
- 📈 Monitor **year-over-year (YoY) trends** in sales, profit, and customer growth.  
- 🏆 Identify **top-performing products and high-value customers**.  
- ⚠️ Detect **profitability risks** in specific categories.  
- 👤 Understand **customer loyalty and behavior patterns** to support better decision-making.

## 📂 **Dataset**

The dashboard is powered by **4 datasets**:  
- 📊 1 Fact Table (Sales Transactions)  
- 🗂️ 3 Dimension Tables (Products, Customers, and Orders)  

👉 [Access the dataset here](dataset)

## 🛠️ **Skills Showcased**

- 🧩 **Data Modeling** → Built a star schema with fact and dimension tables linked by primary/foreign keys.  
- 🔄 **ETL Process** → Cleaned and transformed raw data (e.g., formatting numbers, standardizing units) for analysis.  
- 📊 **Data Visualization** → Selected the most effective chart types for each insight (trends, comparisons, and distributions).  
- 🧮 **Calculated Fields** → Created new measures such as **YoY Growth**, **Profit Ratio**, and **Sales per Customer**.  
- 🎛️ **Parameters & Filters** → Enabled **year selection** for dynamic annual analysis.  
- 🗂️ **Dashboard Navigation** → Designed navigation buttons to toggle between Sales and Customer views.  
- 🎨 **Design Principles** → Applied clean layouts, consistent hierarchy, and blue-yellow highlights for a professional look.   

## 📊 **Dashboard Overview**

### 🛒 Sales Dashboard
![alt text](<resources/Sales Dashboard.png>)

### 👥 Customer Dashboard
![alt text](<resources/Customer Dashboard.png>)
 
## 🔑 **Key Insights**

### 🛒 Sales Performance Insights (2023)

* 📈 **Strong Overall Growth:** The business demonstrated robust year-over-year (YoY) growth across all key metrics: **Total Sales** grew by **20.36%** to **$733K**, **Total Profit** increased by **14.24%** to **$93K**, and **Total Quantity** sold surged by **26.83%**.  
* ⚠️ **Potential Margin Compression:** While profit is growing, it is not keeping pace with the growth in sales and quantity. This suggests a potential decrease in profit margins, possibly due to a shift in product mix towards less profitable items, increased costs, or pricing strategies.  
* 🏆 **Identification of Key Profit Drivers:** **Phones** and **Chairs** are the clear top-performing sub-categories, driving the majority of both sales and profit. These are the company's core assets and should be a focus for marketing and inventory management.  
* 🚨 **Critical Profitability Issues:** The dashboard immediately flags **Tables**, **Bookcases**, and **Supplies** as significant loss leaders. Despite generating substantial sales, these categories are actively draining profit from the business and require urgent strategic review.  
* 📅 **Seasonal Sales Trends:** Sales and profit exhibit strong seasonality, with a noticeable peak in the last quarter (**October-December**) and a significant dip in **April**. This insight is crucial for planning inventory, staffing, and marketing campaigns.  

### 👥 Customer Behavior Insights (2023)

* 📦 **Growing Order Volume Outpaces Customer Growth:** While the number of **Total Customers** grew by a healthy **8.62%**, the number of **Total Orders** saw a massive **28.29%** increase. This indicates that growth is primarily being driven by increased purchasing frequency from both new and existing customers.  
* 💳 **Decreasing Average Customer Value:** A critical insight is the **7.94% decrease** in **Sales Per Customer**. This reinforces the finding from the sales page: the company is selling more items, but the average transaction value per customer is declining. The focus has shifted from high-value purchases to higher volume.  
* 👤 **Large Base of One-Time Buyers:** The customer distribution chart reveals that a significant portion of the customer base (**~58%**) has only made one or two purchases. This highlights a major opportunity to implement retention strategies and convert infrequent shoppers into loyal, repeat customers.  
* 🌟 **High-Value Customer Segment:** A small group of top customers, led by **Raymond Buch** and **Hunter Lopez**, contributes disproportionately to the company's profit. Nurturing these high-value relationships is essential for sustained profitability.  

## 🖥️ **How to Use**  

1. **Access the Dashboard**  
   - 🌐 View on Tableau Public → [Business Performance Dashboard](https://public.tableau.com/views/BusinessPerformanceDashboard_17586779236070/SalesDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)  
   - 💾 Download the `.twbx` file → [Business Performance Dashboard.twbx](<Business Performance Dashboard.twbx>)

2. **Interact with the Dashboard**  
   - 🔄 Use the **Filter** button to adjust the year and refine analysis.  
   - 🖱️ Click on chart elements (e.g., product category) to filter and drill down dynamically.  
   - ⏩ Switch between **Sales** and **Customer** views using the navigation buttons.  