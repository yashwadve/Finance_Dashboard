# FinSight Dashboard

💰 **FinSight: Finance Analysis Dashboard**
An interactive Power BI dashboard delivering real-time insights into transactions, customers, and risk for a finance business.

## Short Description 
A Power BI report analyzing 15K+ transactions worth ₹135.62M to track transaction trends, fees, tax, and customer behavior — built for finance analysts and business decision-makers to monitor performance and risk in real time.

## Tech Stack
- 📊 **Power BI Desktop** – Report creation
- 🟡 **Power Query** – Data cleaning & transformation
- 🔢 **DAX** – Calculated measures (Total Amount, Avg Transaction Value, Total Fees/Tax)
- 🔗 **Data Modeling** – Relationships between Transactions and Customers tables, with slicers for Year, Occupation, Category
- 📁 **File Format** – `.pbix` (development), `.png` (preview)

## Data Source
Two linked CSV tables:
- `finance_transactions.csv` – 50,069 records covering transaction ID, date, account/customer ID, type, channel, merchant category, amount, fees, tax, status, fraud flag, and risk score.
- `customers.csv` – 5,000 records covering customer ID, name, gender, DOB, city, state, occupation, segment, annual income, and join date.

Tables are joined on Customer ID, cleaned in Power Query, then loaded into the data model.

## Features / Highlights
**Business Problem:** Finance teams need a real-time, consolidated view of transaction volume, value, and risk across customer segments — hard to track manually across thousands of daily transactions.

**Goal:** A single dashboard to monitor transaction performance, fees/tax trends, and customer segment behavior, filterable by year, occupation, and category.

**Key Visuals:**
- KPI cards – Total Amount (₹135.62M), Transactions (15.03K), Avg Value (₹9.02K), Fees (₹217.30K), Tax (₹39.14K), all with YoY % change
- Transactions table – per-transaction detail (customer, type, status, gender, segment, state, amount, fees, tax)
- Monthly trend – Total Transactions by Month
- Status donut – Success/Failed/Pending split
- Customer Segment & Gender breakdown
- State-wise transaction bar chart
- Transaction Type Analysis table – Amount, Fees, Tax, Transactions per type

**Insights:**
- Total transaction value fell slightly YoY (-1.06%), while fees and tax rose marginally
- Success rate is high at 85.5%, with only 4.2% failed transactions
- Retail is the dominant customer segment (8.1K transactions), followed by Premium and SME
- Maharashtra and Karnataka lead in state-wise transaction volume
- Loan EMI and Transfer are the largest transaction types by amount (₹39.9M and ₹35.7M)
- Transactions are fairly gender-balanced (51% male, 49% female)

## Screenshots 
Show what the dashboard looks like.
![Dashboard Preview](https://github.com/yashwadve/Finance_Dashboard/blob/main/Finance%20Dashboard%201.png)

![Dashboard Preview](https://github.com/yashwadve/Finance_Dashboard/blob/main/Finance%20Dashboard%202.png)
