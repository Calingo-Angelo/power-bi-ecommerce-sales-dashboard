# Olist E-Commerce Sales Dashboard

Executive Power BI dashboard built to analyze sales performance, customer reviews, product categories, and payment trends using the Olist Brazilian E-Commerce dataset. This project demonstrates end-to-end business intelligence skills including data preparation, data modeling, DAX calculations, dashboard development, and business insight generation.

![Dashboard Overview](images/dashboard-overview.png)

---

# Project Overview

This project transforms multiple raw e-commerce datasets into a business intelligence dashboard for monitoring company performance. Using Microsoft Power BI, the dashboard provides an executive view of revenue trends, customer satisfaction, product category performance, and payment behavior.

The dashboard was built using Power Query for data transformation, a star schema data model for efficient relationships, DAX measures for business calculations, and interactive Power BI visualizations.

---

# Business Objectives

The dashboard was designed to answer questions such as:

- How has revenue changed over time?
- Which product categories generate the most revenue?
- How satisfied are customers based on review scores?
- Which payment methods account for the largest share of revenue?
- What are the company's key performance indicators?

---

# Dashboard Features

## Executive KPI Cards

The dashboard includes executive KPI cards displaying:

- Total Revenue
- Total Orders
- Average Order Value
- Average Review Score
- Average Delivery Days

![KPI Cards](images/dashboard-kpis.png)

---

## Business Visualizations

The dashboard includes:

- Monthly Revenue Trend
- Top Product Categories by Revenue
- Customer Review Score Distribution
- Revenue by Payment Type

These visualizations provide a high-level overview of business performance while allowing users to quickly identify important trends.

![Dashboard Charts](images/dashboard-charts.png)

---

# Data Preparation

The raw datasets were cleaned and transformed using **Power Query**.

Major preparation steps included:

- Imported multiple CSV datasets
- Built relationships using a star schema
- Merged product category translations into the Products table
- Replaced missing product categories with **"Unknown"**
- Standardized category names
- Created a Calendar table for time-based analysis
- Configured appropriate data types for all tables

---

# Data Model

The dashboard follows a **star schema** centered around Orders and Order Items.

Dimension tables include:

- Customers
- Products
- Sellers
- Payments
- Reviews
- Calendar

This modeling approach improves performance, simplifies calculations, and follows common business intelligence best practices.

---

# DAX Measures

Custom DAX measures were created to calculate business metrics including:

- Total Revenue
- Total Orders
- Average Order Value
- Average Review Score
- Average Delivery Days

These measures power the dashboard KPIs and visualizations.

---

# Key Business Insights

Analysis of the dashboard revealed several business insights:

- Revenue increased steadily throughout most of the available time period.
- Health Beauty and Watches Gifts generated the highest revenue among product categories.
- Most customer reviews received the maximum rating of **5**, indicating generally high customer satisfaction.
- Credit cards accounted for approximately **78% of total payment value**.

---

# Skills Demonstrated

This project demonstrates experience with:

- Microsoft Power BI
- Power Query
- DAX
- Data Modeling
- Star Schema Design
- Data Cleaning
- Data Transformation
- Dashboard Development
- Data Visualization
- KPI Development
- Business Intelligence
- Git & GitHub

---

# Tools Used

- Microsoft Power BI Desktop
- Power Query
- DAX
- GitHub

---

# Dataset

This project uses the **Brazilian E-Commerce Public Dataset by Olist**, available on Kaggle.

**Dataset Source**

[Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

The dataset contains information about:

- Customers
- Orders
- Order Items
- Products
- Sellers
- Payments
- Customer Reviews
- Product Category Translations

---

# Repository Structure

```text
olist-powerbi-sales-dashboard/
│
├── images/
│   ├── dashboard-overview.png
│   ├── dashboard-kpis.png
│   └── dashboard-charts.png
│
└── README.md
```

---

# Future Improvements

Potential future enhancements include:

- Interactive dashboard filtering
- Customer segmentation analysis
- Geographic sales analysis
- Profitability analysis
- Sales forecasting

---

## Author

**Angelo Calingo**

Recent Computer Science graduate with an interest in Business Intelligence, Data Analytics, and Real Estate Analytics.
