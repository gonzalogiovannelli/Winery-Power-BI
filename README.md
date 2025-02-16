# Power BI Wine Dashboard

This Power BI dashboard provides a comprehensive **financial and inventory analysis** for a wine business.  
It includes key insights on **account balances, supplier debt, wine stock levels, and monthly results**.

🔗 **View the full Power BI report here:** [Click to Open](https://app.powerbi.com/view?r=eyJrIjoiZTM0ZGFmZmItMWZkMC00ODEzLThhZDEtODYyZDlhZGExMjgwIiwidCI6ImJhMWRhMTIzLTdhOTktNDlhNy05Yjk1LWQ2ZGUwOWJjM2RlYSIsImMiOjR9)

## 📊 Project Overview

This Power BI dashboard is designed to provide **financial insights and inventory tracking** for a wine business.  
It helps stakeholders make data-driven decisions by visualizing **monthly results, supplier debts, and stock levels**.

### 🔹 Key Features:
- **Financial Overview**: Tracks **account balances**, **net assets**, and financial performance.
- **Sales Analysis**: Visualizes **monthly revenue trends** from different sources.
- **Supplier Debt Tracking**: Monitors outstanding payments to suppliers.
- **Wine Inventory Management**: Displays **stock levels** and their valuation by winery.
- **Database Snowflake Model**: Optimized relational model for seamless reporting.

### 🛠 Tools Used:
- **Power BI** for interactive data visualization.
- **DAX (Data Analysis Expressions)** for calculations and measures.
- **Relational Database (Snowflake Schema)** for structured data modeling.

## 🗂 Database Structure & Tables

This Power BI dashboard is built using a **Snowflake Schema**, ensuring efficient data relationships and performance.

### 🔹 Main Tables:

- **Ventas (Sales)**: Stores **transaction data, revenue sources, and amounts** for analysis.
- **Saldos (Account Balances)**: Tracks **bank balances and financial statements**.
- **Proveedores (Suppliers)**: Lists **supplier names and outstanding debts**.
- **Inventario (Inventory)**: Manages **wine stock levels, valuations, and winery details**.
- **Calendario (Calendar Table)**: A **date reference table** for time-based analysis.
- **Pagos (Payments & Expenses)**: Stores **business expenses, invoices, and financial movements**.

📌 This relational model allows **efficient filtering, aggregation, and financial analysis** across all reports.
