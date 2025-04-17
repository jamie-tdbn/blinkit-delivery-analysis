# 🛒 Blinkit: Enhancing Operational Efficiency through Delivery Performance Analysis

**Goal:**  
Analyze delivery performance data from Blinkit to identify inefficiencies, improve operational KPIs, and boost customer satisfaction.

---

## 📊 Tools Used
- Power BI
- DAX

---

## 📁 Dataset Overview
The dataset simulates Blinkit's e-commerce and logistics operations, organized across seven structured tables:

### 🧾 `blinkit_orders`
Contains master-level order information:
- `order_id`, `customer_id`, `order_date`
- `promised_delivery_time`, `actual_delivery_time`, `delivery_status`
- `order_total`, `payment_method`, `delivery_partner_id`, `store_id`

### 📦 `blinkit_order_items`
Breakdown of items per order:
- `order_id`, `product_id`, `quantity`, `unit_price`

### 🚚 `blinkit_delivery_performance`
Tracks actual delivery execution and logistics:
- `order_id`, `delivery_partner_id`, `promised_time`, `actual_time`
- `delivery_time_minutes`, `distance_km`, `delivery_status`
- `customer_id`, `customer_name`, `email`

### 👥 `blinkit_customers`
Customer demographic and behavioral data:
- `customer_id`, `customer_name`, `email`, `phone`
- `area`, `registration_date`, `customer_segment`
- `total_orders`, `avg_order_value`

### 🛒 `blinkit_products`
Product catalog:
- `product_id`, `product_name`, `category`, `brand`, `price`

### ⭐ `blinkit_customer_feedback`
Customer satisfaction and sentiment:
- `feedback_id`, `order_id`, `customer_id`
- `rating`, `feedback_category`, `sentiment`, `feedback_date`

### 📢 `blinkit_marketing_performance`
Marketing performance tracking:
- `campaign_id`, `campaign_name`, `date`, `target_audience`, `channel`
- `impressions`, `clicks`, `conversions`, `spend`, `revenue_generated`, `roas`

> 📌 Most tables are joinable via `order_id`, `customer_id`, and `product_id`, enabling multi-dimensional analysis.

---

## 📈 Dashboards Included
### 1. **Overview**
- Top 5 Prodcut Categories by Transations
- Top 5 Stores with Highest Sales Value
- Sales Volumn by Month
- Transactions and Sales by Month

### 2. **Customer**
- Total Customers ordered in this period
- Customer Tyoes
- Registered Customers
- Customers Data
- Top 10 Areas with the Most Inactive Customers
- Satisfaction Rate
- AVG Satisfaction Rate
- Feedback
- Which Customer Groups are sending negative feedbacks
- Top 10 Products Receiving the Most Negative Feedbacks (1-3 points)
- Total Customers by Rating of Feedback Categories
- Correlation between Satisfaction Rate and Delivery Time (mins)

### 3. **Products & Operation**
- Bottom 10 Storé with Lowest Sales Value
- Customer Growth
- Total Campaigns by Target Audiences
- Total Campaigns by Channel
- Planned MKT Campaigns by Months
- Planned MKT Campaigns Data
- AVG Delivery Time (mins)
- AVG Delivery Time vs. Satisfaction Rate
- Correlation between Delivery Time & Quantity
- Latness (mins) vs. Product & Quantity
- Delivery Status
- Weekday / Weekend Transactions
- Top 10 Lowest-Sellers
- Peak Day & Time

---

## 📎 Files Included
- `Dashboard_BLINKIT GROCERY SALES ANALYSIS.pbix`: Power BI report file
- `dashboard_screenshots/`: PNG exports of dashboard pages
- `Blinkit Sales Report.pdf`: Report of analysis
- `dataset.zip`: Simulated data used for analysis

---

## 🧠 Techniques Used
- RFM Analysis (Recency, Frequency, Monetary)
- Churn Analysis
- Operational Analysis
- DAX Measures (AVERAGEX, COUNTROWS, SWITCH, etc.)
- Custom tooltips, slicers, dynamic visuals


---

## 🔗 Preview
<img width="1240" alt="image" src="https://github.com/user-attachments/assets/053b4bcf-bb7b-4e28-98bd-7e4662963341" />


---

