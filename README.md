# Olist E-commerce & Marketing Performance Dashboard (2016-2018)

## 📖 Project Overview
This Power BI project presents a comprehensive analysis of the **Olist E-commerce public dataset**, covering the years 2016 to 2018. The dashboard is designed to provide stakeholders with a holistic view of the business's performance, breaking down complex data into actionable insights across Sales, Logistics, Marketing, and Customer Behavior.

The project demonstrates advanced data modeling, visualization best practices, and business acumen in transforming raw transactional data into a strategic decision-making tool.

## 🎯 Key Business Objectives
The dashboard answers critical business questions such as:
- **Financial Health:** What are the total revenue trends and Average Order Values (AOV)?
- **Operations & Logistics:** What is the delivery performance and on-time delivery rate across different days and regions?
- **Marketing ROI:** How effective are our marketing channels in converting leads into sales?
- **Customer Retention:** What is the ratio of new vs. returning customers, and how does customer acquisition change over time?
- **Category Performance:** Which product categories generate the most revenue, and which have the highest unit sales?

## 🛠️ Technical Stack
- **Tool:** Microsoft Power BI Desktop
- **Data Source:** Olist Brazilian E-commerce Public Dataset (CSV files)
- **Data Transformation:** Power Query (M Language) for cleaning, merging, and shaping.
- **Data Modeling:** Star schema design with Fact and Dimension tables to optimize DAX performance.
- **DAX Measures:** Created calculated measures for KPIs, dynamic time intelligence (Month-over-Month comparisons), and conversion rates.

## 📊 Dashboard Features (Page-by-Page Breakdown)

1.  **📄 Summary (Executive Overview):**
    - High-level KPIs: Total Revenue ($14.27M), Total Orders (99K), Total Customers (96K), Avg Review Score (4.09).
    - Top 10 Sold Product Categories and Total Revenue by Month.
    - Breakdown of Customer Preferred Payment Types.

2.  **👥 Customers:**
    - Customer acquisition trends over time (Monthly/Yearly).
    - Top 10 Cities contributing the most customers.
    - New vs. Returning Customer ratio (Currently 3.12% returning).
    - Donut chart displaying preferred payment methods.

3.  **📦 Orders (Logistics):**
    - Order Volume vs. On-Time Delivery % by Day of Week.
    - Orders Distribution by Delivery Time Group (Fast, Normal, Slow, Late).
    - Distribution of orders based on the number of installments (payment plans).

4.  **🔄 Funnel Performance (Marketing):**
    - Marketing Qualified Leads (MQLs) to Closed Deals conversion.
    - Revenue breakdown by Lead Origin (Organic Search is the highest).
    - Manufacturer vs. Reseller sales split.
    - Conversion Rate % by lead origin.

5.  **🛒 Sellers:**
    - Top 10 Categories by Unique Sellers.
    - Distribution of Seller Review Scores (5-star reviews dominate at 57.83%).
    - Cities with the highest number of sellers.
    - Sellers' Delivery Time (Days) after order approval.

6.  **🏷️ Categories:**
    - Average Order Value (AOV) by Product Category.
    - Total Revenue and Order Volume by Category.
    - Quarterly Revenue Trends for top categories to identify seasonality.

## 📈 Key Insights & Recommendations
- **Seasonality:** Revenue peaks in May ($1.58M). However, a significant drop occurs in September and October. Recommendations: Plan inventory and marketing spends around the May peak and analyze the drop in Q4 to mitigate losses.
- **Logistics Excellence:** While 92% of orders are on time, Sunday has the highest On-Time delivery percentage. Recommendation: Study Sunday logistics to replicate success on other days of the week.
- **Customer Retention:** The 3.12% repeat customer rate is low. Recommendation: Implement a customer loyalty program or targeted email campaigns to increase CLV (Customer Lifetime Value).
- **Marketing Channels:** Organic Search outperforms Paid Search in revenue. Recommendation: Re-evaluate the budget allocation between paid and organic channels to maximize ROI.

## 🚀 How to Use the Dashboard
1.  Download the `.pbix` file from this repository.
2.  Open it in Power BI Desktop (Ensure you have the latest version installed).
3.  Interact with the slicers on the left sidebar (Month/Year) to filter data dynamically.
4.  Click the navigation buttons on the sidebar to switch between dashboards.

## 💬 Feedback
I am open to feedback and suggestions for improvement! If you have any questions about the DAX measures used or the data modeling process, please feel free to reach out or open an issue in this repository.

---

*Developed by Amna Hedhili*
