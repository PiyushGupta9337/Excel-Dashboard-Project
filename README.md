# Vrinda Store — Sales Data Analysis Dashboard

An Excel dashboard built to analyze one year of order data for **Vrinda Store**, a multi-channel apparel retailer. The project turns raw transactional data into an interactive report using **PivotTables and PivotCharts**.

## 📊 Overview

The workbook takes raw e-commerce order data (~28,000+ rows) and summarizes it into key business insights: sales trends, order fulfillment status, customer demographics, top-performing regions, and sales channels.

## 🧾 Dataset

The raw data (`Vrinda Store` sheet) includes order-level details:

| Field | Description |
|---|---|
| Order ID, Cust ID | Order and customer identifiers |
| Gender, Age, Age Group | Customer demographics |
| Date, Month | Order date |
| Status | Delivered / Cancelled / Returned / Refunded |
| Channel | Amazon, Flipkart, Myntra, Ajio, Meesho, Nalli, Others |
| SKU, Category, Size, Qty | Product details |
| Amount | Order value (INR) |
| ship-city, ship-state, ship-postal-code | Shipping location |

## 📈 Dashboard Sheets

- **Report** — Vrinda Store Annual Report 2026 (summary dashboard)
- **Sales VS Orders** — Monthly sales value and order count trends
- **Men VS Women** — Sales split by gender
- **Order Status** — Breakdown of Delivered, Cancelled, Returned, and Refunded orders
- **Top States** — Highest-revenue states (Maharashtra, Karnataka, Uttar Pradesh, etc.)
- **Age & Gender** — Order distribution across Adult, Teenager, and Senior age groups by gender
- **Order Channels** — Share of orders by sales platform (Amazon, Flipkart, Myntra, etc.)

## 🛠️ Built With

- Microsoft Excel
- PivotTables & PivotCharts

## 🔍 Key Insights

- Women customers account for a significantly larger share of sales than men.
- Amazon is the leading order channel, followed by Myntra and Flipkart.
- Maharashtra, Karnataka, and Uttar Pradesh are the top revenue-generating states.
- The vast majority of orders reach **Delivered** status, with a small share cancelled, returned, or refunded.

## 📁 Files

- `Vrinda_Store_Data_Analysis.xlsx` — Full workbook with raw data, pivot tables, and dashboard

## 📌 Note

This is a practice/portfolio project built to demonstrate Excel skills in data cleaning, PivotTables, PivotCharts, and dashboard design.
