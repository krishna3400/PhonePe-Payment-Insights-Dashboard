# 📱 PhonePe Payment Insights Dashboard

![PhonePe](phonepelogo.png)

An interactive **Power BI dashboard** built to analyze PhonePe payment activity, transaction trends, user behavior, service performance, and payment success rates. The dashboard transforms raw transaction data into clear and actionable business insights through interactive visualizations and KPIs.

---

## 📊 Dashboard Preview

![PhonePe Payment Insights Dashboard](phonepe%20dashboard%20%282%29.png)

---

## 🎯 Project Overview

Digital payment platforms generate large volumes of transactional data every day. This project focuses on analyzing PhonePe transaction data to understand payment patterns, user engagement, service performance, and transaction outcomes.

The dashboard provides an interactive view of key metrics and allows users to explore transaction performance across different dimensions.

---

## 🎯 Project Objectives

The main objectives of this project are to:

- Analyze overall transaction volume and transaction value
- Monitor successful, failed, and pending transactions
- Understand transaction trends over time
- Identify high-performing payment services
- Analyze user contribution and engagement
- Compare weekday and weekend usage
- Analyze transaction contribution across age segments
- Present key insights through an interactive Power BI dashboard

---

## 🛠️ Tools & Technologies

- **Power BI** – Dashboard development and visualization
- **DAX** – Calculated measures and KPI analysis
- **Power Query** – Data cleaning and transformation
- **Excel** – Dataset and data preparation

---

## 📌 Key Performance Indicators

| KPI | Value |
|---|---:|
| Total Transactions | 300K |
| Total Transaction Value | ₹3.47B |
| Unique Users | 108K |
| Successful Rate | 96% |

---

## 📈 Dashboard Features

### 💳 Transaction Overview

The dashboard provides an overview of total transactions, total transaction value, unique users, and successful transaction rate.

### 📅 Transactions Over Time

Analyzes transaction activity across different months to identify fluctuations, peaks, and changes in payment behavior.

### 🏦 Service Transaction Value

Compares transaction value across different services such as:

- Loans
- Insurance
- Money Transfer
- Recharge & Bill Payments

This helps identify services contributing the most transaction value.

### 👥 User Analysis

Identifies the top users based on transaction value and provides insights into user contribution to the platform.

### 🎂 Age Segment Analysis

Analyzes transaction contribution across different age groups to understand user demographics and payment behavior.

### 📆 Weekday vs Weekend Usage

Compares transaction activity between weekdays and weekends to identify differences in user payment behavior.

### ✅ Payment Status Analysis

Tracks successful, failed, and pending transactions to evaluate overall payment performance and reliability.

---

## 💡 Key Insights

- **300K transactions** generated a total transaction value of **₹3.47B**.
- The overall **successful transaction rate is 96%**.
- **108K unique users** contributed to the analyzed transactions.
- **Loan services** recorded the highest transaction value among the analyzed services.
- **Weekday usage is higher than weekend usage**, indicating stronger payment activity during weekdays.

---

## 📊 Dashboard KPIs

The dashboard uses interactive KPI cards and visualizations to provide a quick overview of:

**Transactions → Transaction Value → Users → Success Rate**

Users can also interact with filters to explore the data based on different payment conditions and time periods.

---

## 🧹 Data Preparation

The dataset was prepared using **Power Query** before being used for dashboard development.

The preparation process included:

- Removing unnecessary data
- Handling missing values
- Checking data types
- Transforming columns
- Creating required fields
- Preparing data for analysis and visualization

---

## 🧮 DAX & Calculations

DAX measures were created to calculate important business metrics such as:

- Total Transactions
- Total Transaction Value
- Unique Users
- Successful Transaction Rate
- Service-wise Transaction Value
- User contribution
- Time-based transaction metrics

These measures were then used throughout the dashboard to create dynamic KPIs and visualizations.

---

## 📂 Repository Structure

```text
PhonePe-Payment-Insights/
│
├── Background.png
├── Colors.png
├── LICENSE
├── Phonepe-Final-Dataset.xlsx
├── README.md
├── phonepe dashboard (2).png
├── phonepe.pbix
└── phonepelogo.png
