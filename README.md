# 🛒 E-Commerce Seller Performance & Logistics Analytics

## 📌 Project Overview
This project analyzes the operational performance, logistics efficiency, and customer satisfaction of an e-commerce platform using the Olist Brazilian E-Commerce dataset. By processing over 100,000 orders and customer reviews, this dashboard identifies high-value merchants and exposes the direct impact of supply chain speed on brand reputation.

## 🛠️ Tools & Technologies Used
* **Database Management:** MySQL (Bulk imported raw CSVs using `LOAD DATA INFILE` for optimal performance)
* **Data Manipulation:** SQL (Complex Joins, Aggregations, Date/Time formatting)
* **Data Visualization:** Tableau (Interactive mapping, parameter filtering, and dashboard design)


## ❓ Core Business Questions
1. Who are the highest-value sellers, and what is the platform's revenue concentration?
2. Which geographic regions generate the highest sales volume?
3. How severely do delivery delays impact customer satisfaction (Review Scores)?


## 📊 Final Dashboard
<img width="1657" height="851" alt="E-Commerce Seller Performance   Logistics Dashboard" src="https://github.com/user-attachments/assets/c5384e80-de84-47d5-a46a-ebea26de7f43" />


## 🔎 Deep Dive & Key Business Insights

### 1. Geographic Supply Chain Concentration
<img width="1240" height="762" alt="Screenshot 2026-08-19 012142" src="https://github.com/user-attachments/assets/1ca53429-f209-4d5f-b434-80f9431b087f" />


**The Insight:** 
Platform revenue and merchant activity are heavily clustered in major economic hubs, with São Paulo (SP) acting as the primary anchor. From a business development perspective, this data suggests that future seller onboarding campaigns and logistics investments should prioritize these high-density regions to maximize return on investment and minimize localized shipping bottlenecks.

### 2. Identifying High-Value Merchants (Top 10 Sellers)
<img width="1437" height="337" alt="Screenshot 2026-08-19 124014" src="https://github.com/user-attachments/assets/54b698ea-15a7-446d-9f8c-d8308926265f" />


**The Insight:**
Visualizing the top sellers by total revenue reveals a stark concentration of sales volume among a select group of high-performing merchants. Understanding this distribution is critical for proactive client management; establishing dedicated support or tiered retention initiatives for these specific accounts is essential to protecting the platform's baseline revenue.

### 3. Delivery Speed vs. Customer Satisfaction
<img width="1447" height="768" alt="Screenshot 2026-08-19 012120" src="https://github.com/user-attachments/assets/460c840b-5b33-4ede-b596-b5ffcdfa4fa0" />


**The Insight:**
There is a direct, quantifiable correlation between delivery speed and customer review scores. Five-star reviews consistently align with the shortest delivery windows, while shipping delays sharply drive the average rating down to one star. This proves that investing in logistics and enforcing strict merchant shipping limits is not just an operational necessity, but a core driver of customer retention and platform trust.


## 📁 Files in this Repository
* `ecommerce data analytics.sql`: The raw SQL code used to extract, join, and aggregate the raw datasets into analytical tables.
* `Ecommerce_Seller_Performance.twbx`: The packaged Tableau workbook containing the interactive dashboard.
