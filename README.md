# Retail Sales & Business Performance — Excel

## 📌 Project Overview

Retail Sales & Business Performance is an end-to-end Excel data analytics project built to analyze retail transaction data and generate actionable business insights.

The project covers the complete analytics workflow:

Raw Data → Power Query Cleaning → Data Transformation → Business Analysis → PivotTables → Interactive Dashboard → Business Insights

The objective is to understand revenue, profitability, product performance, customer behavior, regional performance, sales channels, salesperson performance, and discount impact.

---

## 🎯 Business Problem

The business needs a consolidated view of its sales performance to understand:

- Overall revenue and profitability
- Monthly revenue trends
- Category and product performance
- Regional performance
- Sales channel contribution
- Customer revenue and purchasing behavior
- Salesperson performance
- Relationship between discounts and profitability
- Products requiring closer monitoring

The analysis was designed to transform raw transactional data into a structured reporting and decision-support solution using Microsoft Excel.

---

## 📂 Dataset

The dataset contains retail transaction-level data covering approximately 12 months of sales activity.

### Dataset Characteristics

- Raw records: 2,508
- Duplicate records identified: 8
- Final cleaned records: 2,500
- Unique customers: 497
- Products: approximately 30
- Categories: 7
- Regions: 4
- Sales channels: 3
- Salespersons: 15 + Unknown

### Key Columns

- Order_ID
- Order_Date
- Customer_ID
- Customer_Name
- Product_ID
- Product
- Category
- Region
- City
- Salesperson
- Quantity
- Unit_Price
- Discount
- Sales
- Cost
- Profit
- Sales_Channel
- Payment_Method
- Order_Status

The raw dataset intentionally contained data-quality issues such as duplicate records, extra spaces, inconsistent capitalization, missing values, and date/time formatting issues.

---

## 🛠️ Tools & Technologies

- Microsoft Excel
- Power Query
- PivotTables
- PivotCharts
- Slicers
- Excel Formulas
- Data Cleaning
- Data Transformation
- Exploratory Data Analysis
- Business Analysis
- Data Visualization
- Dashboard Development

---

## 🔄 Data Cleaning & Transformation

Power Query was used to transform the raw dataset into a clean analytical dataset.

### Cleaning Steps

- Corrected data types
- Removed 8 exact duplicate records
- Trimmed unnecessary spaces
- Standardized region names
- Standardized payment methods
- Handled missing salesperson values
- Handled missing city values
- Handled missing payment methods
- Converted Order_Date to date-only format
- Validated Quantity, Unit_Price, Discount, Sales, Cost, and Profit
- Standardized salesperson names using a master mapping
- Loaded the final cleaned dataset into the `clean_data` sheet

### Data Preparation Workflow

Raw Data
    ↓
Power Query
    ↓
Data Cleaning & Transformation
    ↓
Clean Dataset
    ↓
Business Analysis
    ↓
PivotTables & PivotCharts
    ↓
Interactive Dashboard
    ↓
Business Insights

---

## 📊 Key Performance Indicators

| KPI | Value |
|---|---:|
| Total Revenue | ₹60,088,438.55 |
| Total Profit | ₹14,439,832.55 |
| Profit Margin | 24.03% |
| Total Orders | 2,500 |
| Units Sold | 5,949 |
| Average Order Value | ₹24,035.38 |
| Total Customers | 497 |
| Average Discount | 9% |

---

## 📈 Business Analysis

### 1. Overall Business Performance

The analysis evaluates:

- Total Revenue
- Total Profit
- Profit Margin
- Total Orders
- Units Sold
- Average Order Value
- Total Customers
- Average Discount

### 2. Revenue Analysis

The project analyzes:

- Monthly Revenue Trend
- Revenue by Category
- Revenue by Region
- Revenue by Sales Channel
- Top Products by Revenue

### 3. Product Analysis

Product-level analysis includes:

- Top 10 Products by Revenue
- Top 10 Products by Profit
- Products by Units Sold
- Bottom 10 Products by Revenue

### 4. Customer Analysis

Customer analysis includes:

- Top Customers by Revenue
- Top Customers by Profit
- Customer Order Frequency
- One-time vs Repeat Customers

### 5. Salesperson Analysis

Salesperson performance was evaluated using:

- Revenue
- Profit
- Order Volume

### 6. Discount & Profitability Analysis

The analysis evaluates:

- Discount vs Sales
- Discount vs Profit
- Profit Margin by Discount
- High-Discount / Low-Profit Products

---

## 💡 Key Business Insights

### 1. Strong Revenue Concentration in Electronics

Electronics generated ₹32.95M, contributing approximately 54.8% of total revenue and ₹7.60M in profit. The business therefore has a strong dependence on the Electronics category.

### 2. South Region Leads Profit Contribution

The South region generated approximately ₹4.15M in profit, followed by West at ₹3.76M, North at ₹3.48M, and East at ₹3.05M.

### 3. Higher Discounts Are Associated with Lower Profit Margins

Profit margin declined across the observed discount levels:

- 0% discount → 31%
- 5% discount → 27%
- 10% discount → 24%
- 15% discount → 20%
- 20% discount → 14%

This indicates an association between higher discount levels and lower profitability in the dataset.

### 4. Mouse Is the Leading Product

Mouse generated approximately ₹10.14M in revenue and ₹3.30M in profit, making it the strongest individual product contributor in the analysis.

### 5. Store Channel Generates the Highest Revenue

The Store channel generated approximately ₹21.85M, followed by Online at ₹20.60M and Marketplace at ₹17.63M.

### 6. High Repeat-Customer Participation

Out of 497 unique customers, 478 were repeat customers while 19 were one-time customers.

### 7. Regional Revenue Is Relatively Balanced

Revenue across the four regions was:

- South — ₹16.97M
- West — ₹15.63M
- North — ₹14.29M
- East — ₹13.20M

Unlike category performance, revenue was relatively distributed across regions.

### 8. High-Discount / Low-Profit Products

Using discount ≥10% and profit <₹100K as analytical thresholds, Face Wash and Jacket were identified for closer monitoring.

> These findings represent patterns observed in the dataset and should not be interpreted as proof of causal relationships.

---

## 📊 Interactive Dashboard

The project includes an interactive Excel dashboard designed to provide a consolidated view of business performance.

### KPI Cards

- Total Revenue
- Total Profit
- Profit Margin
- Total Orders
- Total Customers
- Average Order Value

### Dashboard Visualizations

- Monthly Revenue Trend
- Revenue by Category
- Revenue by Region
- Revenue by Sales Channel
- Top 10 Products by Revenue
- Salesperson Performance
- Profit Margin by Discount
- Revenue Mix by Category
- Revenue Mix by Sales Channel

### Interactive Filters

- Month
- Category
- Region
- Sales Channel
- Discount

---

## 📁 Workbook Structure

```text
Retail_Sales_Business_Performance_Analysis.xlsx

├── Raw_Data
├── clean_data
├── KPI_Analysis
├── Pivot_Table
├── Analysis_Pivots
└── Dashboard

Sheet Description
| Sheet             | Purpose                                         |
| ----------------- | ----------------------------------------------- |
| `Raw_Data`        | Original raw transactional dataset              |
| `clean_data`      | Cleaned and transformed dataset                 |
| `KPI_Analysis`    | KPI calculations and business metrics           |
| `Pivot_Table`     | PivotTables supporting dashboard visualizations |
| `Analysis_Pivots` | Detailed analytical PivotTables                 |
| `Dashboard`       | Interactive business performance dashboard      |

🎯 Project Outcome

This project demonstrates an end-to-end Excel Data Analytics workflow, from raw data cleaning and transformation to exploratory analysis, KPI development, PivotTable analysis, interactive dashboard creation, and business insight generation.

The project demonstrates practical skills relevant to:

Data Analyst
MIS Analyst
Business Analyst
Reporting Analyst

👤 Author

Soumya Ranjan Sahoo

MCA | Data Analytics | SQL | Excel | Power BI | Python
