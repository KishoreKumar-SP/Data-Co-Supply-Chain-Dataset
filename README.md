# 📦 Supply Chain & Delivery Performance Analytics – Tableau

## 📊 Project Overview

This project is an interactive **Supply Chain & Delivery Performance Analytics Dashboard** developed using **Tableau**. The goal is to analyze sales, orders, shipping performance, delivery status, customer locations, product categories, and logistics efficiency.

The dashboard transforms raw supply chain data into meaningful visual insights that can help businesses monitor operational performance and identify delivery and shipping issues.

## 🎯 Objectives

- Analyze overall sales and order performance.
- Monitor delivery and shipping efficiency.
- Identify late-delivery patterns and delivery risks.
- Compare actual shipping time with scheduled shipping time.
- Analyze sales and performance across product categories and regions.
- Understand shipping-mode performance.
- Identify areas that may require operational improvement.

## 🛠️ Tools & Technologies

- **Tableau** – Data visualization & dashboard development
- **Microsoft Excel** – Dataset/source data
- **Data Cleaning & Transformation**
- **Calculated Fields**
- **Interactive Filters & KPIs**
- **Data Visualization**

## 📁 Dataset

The project uses the **DataCo Supply Chain Dataset**, containing information related to:

- Orders and sales
- Customers
- Products and categories
- Shipping modes
- Delivery status
- Shipping duration
- Scheduled shipping time
- Customer locations
- Order quantities
- Benefits and sales performance

## 📈 Dashboard Analysis

The Tableau workbook contains multiple analytical views covering:

### 🔹 KPI Analysis
- Total Orders
- Total Sales
- Total Quantity
- Average Shipping Days
- Average Scheduled Shipping Days
- Late Delivery Orders
- On-Time Shipping Orders

### 🔹 Delivery Performance
- Delivery Status Analysis
- Delivery Performance Distribution
- Actual vs Scheduled Shipping
- Regional Delivery Performance
- Delivery Performance & Benefit Analysis

### 🔹 Sales & Product Analysis
- Category Revenue Analysis
- Category-level Sales & Delivery Performance
- City-wise Category and Product Analysis
- Benefit per Order

### 🔹 Logistics Analysis
- Shipping Mode Analysis
- Monthly Order Trends
- Shipping delays and delivery risk analysis

## 🧮 Key Calculations

The project uses Tableau calculated fields to derive important business metrics.

### Shipping Delay

```text
Actual Shipping Days - Scheduled Shipping Days
```

### Shipping Performance

```text
IF [Shipping Difference] > 0 THEN "Delayed"
ELSEIF [Shipping Difference] = 0 THEN "On Schedule"
ELSE "Early"
END
```

These calculations help classify shipments based on whether they were delivered early, on schedule, or with a delay.

## 🔍 Key Business Questions

This project helps answer questions such as:

1. How many orders are being processed?
2. What is the overall sales performance?
3. How many orders have delivery delays?
4. Which shipping modes have higher delivery risks?
5. How does actual shipping time compare with scheduled shipping time?
6. Which product categories generate higher revenue?
7. Which regions experience more delivery issues?
8. How do delivery performance and customer benefits relate?
9. What are the monthly order trends?
10. Which areas require closer supply-chain monitoring?

## 📊 Tableau Visualizations

The workbook includes visualizations for:

- KPI Cards
- Bar Charts
- Line Charts
- Distribution Charts
- Category Analysis
- Regional Analysis
- Shipping Mode Analysis
- Delivery Status Analysis
- Monthly Trends
- Actual vs Scheduled Shipping Comparison

## 💡 Business Value

The analysis provides a centralized view of supply chain performance and can help organizations:

- Monitor logistics KPIs
- Detect delivery delays
- Track shipping efficiency
- Understand sales and category performance
- Identify high-risk delivery areas
- Compare shipping modes
- Support data-driven operational decisions

## 📂 Project Structure

```text
Supply-Chain-Analytics/
│
├── DataCoSupplyChainDataset.xlsx
├── DataCoSupplyChainDataset.twb
└── README.md
```

## 🚀 How to Use

1. Download or clone this repository.
2. Open the `.twb` file using **Tableau Desktop**.
3. If required, update the Excel data-source path.
4. Refresh the data connection.
5. Explore the worksheets and dashboard visualizations.
6. Use filters and interactive charts to analyze supply-chain performance.

## 👨‍💻 Project Skills Demonstrated

**Tableau | Data Visualization | Data Analysis | Supply Chain Analytics | KPI Development | Calculated Fields | Excel | Business Intelligence | Dashboard Development**

## 📌 Project Type

**Intermediate Data Analytics / Business Intelligence Project**

---

⭐ If you find this project useful, feel free to explore the repository and connect with me on LinkedIn.
