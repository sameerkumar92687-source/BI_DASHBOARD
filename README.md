# BI_DASHBOARD
RELIABLE ANALYSIS OF E-COMMERCE SALES
# 📊 Ajanta E-Commerce BI Dashboard

## Overview
This repository contains a **Power BI dashboard** and supporting datasets for analyzing e-commerce sales performance.  
It provides insights into revenue, profit, customer behavior, product categories, and order details, enabling data-driven decision-making.

---

## ✨ Features
- **Key Metrics Summary**
  - Total Sales Amount: 438K
  - Total Profit: 37K
  - Total Quantity Sold: 6K
  - Average Order Value (AOV): 121K

- **Interactive Filters**
  - Quarter selection (Q1–Q4)
  - State selection (All states or specific)

- **Visualizations**
  - 📍 **Sales by State** – Maharashtra leads with ~0.1M sales.
  - 💳 **Quantity by Payment Mode** – COD dominates (44%), followed by UPI, Debit, Credit, EMI.
  - 📅 **Profit by Month** – Seasonal trends with losses in mid-year months.
  - 👥 **Sales by Customer** – Hariwah contributes the highest (~10K).
  - 🛒 **Quantity by Category** – Clothing (63%) is the largest segment.
  - 📦 **Profit by Sub-Category** – Printers generate the highest profit (~10K).

---

## 📂 Dataset
The repository also includes **customer order records** for Mumbai, Maharashtra.  
Sample structure:

| Order ID | Order Date | CustomerName | State       | City   |
|----------|------------|--------------|-------------|--------|
| B-25923  | 27-12-2018 | Gopal        | Maharashtra | Mumbai |
| B-25858  | 13-11-2018 | Uudhav       | Maharashtra | Mumbai |
| B-26099  | 30-03-2018 | Bhishm       | Maharashtra | Mumbai |
| ...      | ...        | ...          | Maharashtra | Mumbai |

This dataset supports the dashboard by providing **transaction-level details** for analysis.

---

## 🛠️ Tech Stack
- **Power BI** – Data visualization and dashboard creation
- **Data Sources** – CSV/Excel files (Orders, Customers, Products, Transactions)
- **ETL** – Basic data cleaning and transformation within Power BI

---

## 🚀 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/bi-dashboard.git

