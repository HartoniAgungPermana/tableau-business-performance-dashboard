# 📊 **Tableau Business Performance Dashboard — Portfolio Project**

<p align="center">
  <img src="resources/Dashboard Demo.gif" alt="Business Performance Dashboard Demo" />
</p>

This project is a **Tableau-based interactive dashboard** designed for a fictional retail company. The primary objective is to transform raw transactional data into a strategic asset that provides a clear and cohesive view of the company's performance from 2021 to 2023.

The dashboard moves beyond static reporting by offering a dynamic, dual-view analysis platform for key stakeholders, including C-suite executives, sales managers, and marketing strategists. It addresses critical business questions by focusing on two core pillars:

- 🛒 **Sales Performance**: This view analyzes key financial metrics such as **Total Sales, Profit, and Quantity Sold**. It drills down into product-level performance, identifying top-performing categories and flagging those that are unprofitable, while also tracking weekly and seasonal trends.

- 👥 **Customer Behavior**: This view focuses on customer-centric metrics, including **Customer Growth, Order Volume, and Sales per Customer**. It segments the customer base by purchasing frequency to uncover patterns related to loyalty and retention.

By integrating these two perspectives into a single, seamless interface with year-over-year filtering capabilities, the dashboard empowers decision-makers to diagnose business health, identify growth opportunities, and uncover hidden risks.

## 📂 **Dataset**

The dashboard is powered by **4 datasets**:  
- 📊 1 Fact Table (Sales Transactions)  
- 🗂️ 3 Dimension Tables (Products, Customers, and Orders)  

👉 [Access the dataset here](dataset)

# 💼 **Executive Summary**
### [**🛒 Live Dashboard on Tableau Public**](https://public.tableau.com/views/BusinessPerformanceDashboard_17586779236070/SalesDashboard?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)

![alt text](<resources/Sales Dashboard.png>)
![alt text](<resources/Customer Dashboard.png>)

The company has achieved an outsanding top-line growth, indicating that the company is in a period of rapid expansion. Over the last four years, the business has shown impressive growth across all primary metrics. **Total Sales** surged by approximately **51%**, from $484K in 2020 to $733K in 2023. This was driven by a remarkable **74.2%** increase in Total Orders (0.97K to 1.69K). This performance signals strong product-market fit and a successful customer acquisition strategy.

Despite the impresive growth over the past four years, a deeper analysis of underlying data reveals critical challenges related to profitability and customer retention that require immediate strategic attention:

**The Underlying Challenges:**

1. **Chronic Product Losses**: Specific product categories are consistently draining profitability. For three consecutive years, Tables, Bookcases, and Supplies have generated significant losses, undermining the strong performance of profitable categories like Phones and Chairs.

2. **Profit Margin Erosion**: Despite record sales in 2023, profit growth is decelerating. While sales grew by **20.36%**, profit only grew by **14.24%**.Furthermore, despite gaining astronomically high total sales around **$733K**, the company only get **$93K** profit, showing a massive **~87%** gap between revenue and profit generated. This widening gap suggests that the company is selling more but earning less on each sale. This margin compression is not an isolated issue, it is a **direct result of chronic losses from specific product categories**.

3. **Low Customer Retention**: The company's growth is heavily reliant on acquiring new customers rather than cultivating loyalty from its existing base. While the total number of customers grew steadily, the customer distribution data for 2023 shows a major retention gap where **nearly 58% of customers made only one or two purchases (400 out of 693 total customers)**. This signifies a "leaky bucket" scenario where the high cost of acquisition is not being offset by high customer lifetime value (CLV). This presents a substantial opportunity to drive more sustainable and cost-effective growth by converting single-purchase customers into loyal, repeat buyers.

4. **High Dependence in Few Customers**: Based on the top 10 customers, High-value clients consistently drive significant revenue and profit each year. suggesting a remarkable concentration risk that can affect the company performance if those top customers is shaking. This dependency highlights the importance of **diversification and retention programs**.

**In conclusion, while the company excels at market expansion, the path to sustainable success requires a strategic pivot from focusing purely on sales growth to optimizing for profitability and enhancing customer loyalty.**

# 💡 **Strategic Recommendations**

Based on the insights from the dashboard, here are three actionable recommendations to enhance profitability and drive sustainable growth:

### 1. **Optimize the Product Portfolio to Boost Profitability**

The data clearly flags specific products as "profit drains."

- **Action**: Conduct an immediate **root cause analysis (RCA)** of the profit loss on **Tables, Bookcases, and Supplies** categories. Analyze their supply chain costs, pricing strategy, and return rates.

- **Suggestion**: Experiment with bundling these items with high-profit products like **Phones or Chairs**. If profitability cannot be improved, consider delisting the worst-performing items to cut losses.

### 2. **Launch a Customer Retention & Loyalty Program**

A large base of one-time buyers is a significant risk. Converting them into repeat customers is more cost-effective than acquiring new ones.

- **Action**: Develop targeted marketing campaigns aimed at customers who have only made one purchase.

- **Suggestion**: Implement a tiered loyalty program that rewards repeat purchases. Offer personalized follow-up promotions to first-time buyers within 30 days of their initial transaction to encourage a second order.

### 3. **Address Seasonal Sales Patterns with Strategic Promotions**

Sales and profit consistently peak in Q4 (Oct-Dec) and dip in Q2 (especially April).

- **Action**: Leverage the predictable Q4 peak with **targeted holiday campaigns** and ensure adequate inventory for top performers like Phones and Chairs.

- **Suggestion**: To counter the Q2 slump, launch a **mid-year sales event** or a **promotional campaign** in April. This can smooth out revenue and improve year-round cash flow.

# 🔍 **Deep Dive Insights**

### 🧾 1. **Sales & Profit Dynamics**

- Total sales shows astronomical growth of **~51%**, growing from **~$484K** into **~$733K** yearly revenue generated in past 4 years, highlighting positive business growth and a successful business process.
- Despite having a increasing trend year over year, growing from **~$50K** in 2020 into **~$93K** in 2023 with **86%** growth. The gap between sales and profit is considered too wide. While the company generated ~$733K in a year with ~1.69K total orders, the company only earns $93K profit, meaning that only **12%** of total revenue can be generated into profit. It flags a huge margin between profit and sales that we need to take care of.
- Categories like **Phones and Chairs** consistently deliver over **40% of total profit**, while **Tables, Bookcases, and Supplies constantly draining profitability**. It can be the main reason of the wide margin of profit and sales.

### 👥 2. Customer Retention & Behavior

- Customer count increased steadily **(575 → 693)**, showing a growth business performance and highlighting that the product is fit in the market condition.
- The sales per person (AOV) showing a remarkable growth from **$0.81K** into **$1.06K**, suggesting that customers is more likely to spend more money in each order.
- The customer distribution by number of orders shows that majority of customers is a **one time buyer** in a year period, suggesting a **low customer retention within the year.**. 
- The **top 10 customers contributes in approximately 33% of total profit at 2023**, suggesting high dependency and concentration on a small amount of customers. It is a high-risk condition considering the company only gain a small profit from the whole business process. If this small amount top customer market is shaking, the company will get a remarkable damage that potentially collapse the whole business process.

### 🕒 3. Temporal Trends

- Seasonal patterns show **Q4 peaks due to holiday demand**. For the 4 year consecutive, **both sales and profit trend showing an increasing trend** in those era. Exploiting this trend by increasing sales campaign during this period will reward an astonishing sales and profit.
- **Q2 dips (April–June) in both sales and profit** present opportunities for off-season promotional campaigns.

### 📦 4. Product Portfolio Analysis

- **High Sales ≠ High Profit**. Categories like **Chairs, Binders and Storage** contribute a massive sales but generating little profit in 2023. While **Copiers outstand them by generating 3 times more profit** than those categories with less sales contribution.
- **Tables, Bookcases, Machines, and Supplies** record negative profit in almost all years. The company need a concrete action to mitigate this loss profit to happen again in the next following years.

# 🛠️ **Dashboard Features & Technical Skills**

This dashboard was built to showcase a range of business intelligence and data analysis skills:

- **Data Modeling**: Designed a star schema linking a central sales fact table with dimension tables for products, customers, and orders.
- **Calculated Fields**: Engineered advanced calculations in Tableau, including Year-over-Year (YoY) Growth, Profit Ratio, and Sales per Customer, to surface key performance indicators.
- **Interactive Features**: Implemented parameters for year selection and cross-filtering actions, allowing users to dynamically explore the data and drill down into specific categories or trends.
- **Dual-View Navigation**: Created a seamless user experience with navigation buttons to toggle between the dedicated Sales and Customer dashboards, providing a holistic view of the business within a single interface.
- **Data Visualization & Design**: Applied best practices in visual design, using bar charts, line graphs, and KPIs with a consistent color scheme (blue/yellow highlights) to ensure the dashboard is both aesthetically pleasing and easy to interpret.

# **What I Learned**

Throughout this project, I sharpened my understanding of market and performance analysis in a retail company context, and enhanced my technical skills in **tableau**, helping me to visualize and analyze the data and turn it into meaningful insights.

Here are some important takeaways:

- 📈 **Translating BI Performance**

   This project sharpened my skills to extracting valuable information and insights from chaotic raw data. Giving a broad and depth understanding about *what's going on* in the business process of the company.

- 🎯 **Formulate Strategic Recommendations**

   Transform the understanding of the business process and performances gained from translating the data into actionable recomendation plan to encounter all the problems faced by the company and increase the overall performance. Giving a *so what* aspect of the extracted insights.

- 📊 **Designing Effective and Efficient Visualizations**

   Designing the best chart and visualization for each analysis to get the best visuals to highlight the desired insights.

- 📖 **Storytelling optimization**  

   At its core, data is just **numbers and text**—raw, overwhelming, and often confusing. To make analysis **understandable and persuasive**, storytelling is key. Instead of merely presenting SQL queries, tables, or charts, I built a **narrative story** that transforms complex results into **clear insights** for stakeholders who may not have technical expertise. 

# **Challenges I Faced**

- 📊 **Designing Dashboard Layout**

   Choosing and designing the right dashboard layout that can cover and highlight all the chart in one compact dashboard page comprehensively is the biggest challenge in this project. Especially because its a year over year report, a different design approach is required to design and structured all the chart together

- 🔍 **Analyzing the Visualization**

   Flag the pattern, uderstanding what happened, building a report that covers all the findings, and conclude the best strategic recomendation as the answer of the analysis will always be a challenging but rewarding parts of all data analyst.

- ⚖️ **Balancing breadth and depth**  
  I had to constantly balance between going **deep into detailed analysis** and maintaining a **broad overview** of the data landscape. Striking this balance ensured that insights were comprehensive yet focused.

🎯 This project demonstrates not only my technical ability to build advanced Tableau dashboards, but also my analytical thinking, storytelling skills, and business acumen — translating complex data into actionable insights that drive strategic decisions.

## 🖥️ **How to Use**  

1. **Access the Dashboard**  
   - 🌐 View on Tableau Public → [Business Performance Dashboard](https://public.tableau.com/views/BusinessPerformanceDashboard_17586779236070/SalesDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)  
   - 💾 Download the `.twbx` file → [Business Performance Dashboard.twbx](<Business Performance Dashboard.twbx>)

2. **Interact with the Dashboard**  
   - 🔄 Use the **Filter** button to adjust the year and refine analysis.  
   - 🖱️ Click on chart elements (e.g., product category) to filter and drill down dynamically.  
   - ⏩ Switch between **Sales** and **Customer** views using the navigation buttons.  
