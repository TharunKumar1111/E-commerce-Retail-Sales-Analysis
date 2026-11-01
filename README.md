# 🛒 E-commerce Retail Sales Analysis

An end-to-end Data Analytics project focused on understanding e-commerce sales performance, product profitability, customer purchasing behaviour, and business trends. This project uses **Python** for data cleaning and analysis, **SQL** for business analysis, and **Power BI** for interactive data visualization.

---

## 📌 Overview

E-commerce businesses generate large amounts of data through customer orders, product purchases, payments, and marketing channels. Analyzing this data helps businesses understand their performance, identify profitable products, and make informed business decisions.

This project analyzes retail sales data to uncover meaningful insights across revenue, profit, products, customers, regions, and payment methods.

**Workflow:** Raw Data → Data Cleaning → Exploratory Data Analysis → SQL Analysis → Power BI Dashboard → Business Insights

---

## 🎯 Problem Statement

Understanding sales performance and customer purchasing behaviour is essential for the growth of an e-commerce business. However, raw sales data does not directly provide clear insights into revenue trends, product profitability, customer retention, or regional performance.

The objective of this project is to analyze e-commerce retail data, identify important business patterns, and develop an interactive dashboard that supports data-driven decision-making.

---

## 📂 Dataset

The project uses four datasets containing information about customers, orders, products, and order items.

| Dataset | Description |
|---|---|
| `cleaned_customers` | Customer information and acquisition channels |
| `cleaned_orders` | Order details, dates, payment methods, and status |
| `cleaned_products` | Product names, categories, prices, and costs |
| `cleaned_order_items` | Product quantities, selling prices, and discounts |

**Key columns include:**

- Customer data: `customer_id`, `signup_date`, `state`, `acquisition_channel`
- Order data: `order_id`, `customer_id`, `order_date`, `status`, `payment_method`
- Product data: `product_id`, `product_name`, `category`, `list_price`, `unit_cost`
- Order item data: `quantity`, `unit_price`, `discount_amount`

---

## 🛠️ Tools & Technologies

- **Python:** Pandas, NumPy, Matplotlib, Seaborn
- **Google Colab:** Python development environment
- **SQL:** Data querying and business analysis
- **Power BI:** Interactive dashboards and data visualization
- **DAX:** Measures and KPI calculations
- **Excel:** Data inspection and handling
- **Git & GitHub:** Version control and project documentation

---

## 🔄 Project Steps

1. **Data Loading:** Imported the retail datasets for analysis.
2. **Data Cleaning:**
   - Checked and handled duplicate records.
   - Reviewed missing values and data consistency.
   - Standardized data for analysis.
   - Prepared cleaned datasets for further processing.
3. **Exploratory Data Analysis:** Explored sales patterns, product performance, and customer behaviour using Python.
4. **SQL Analysis:** Performed business analysis using SQL queries to answer important business questions.
5. **KPI Development:** Created DAX measures for revenue, profit, orders, average order value, and repeat purchase rate.
6. **Dashboard Development:** Built an interactive Power BI dashboard to present key business metrics and insights.

---

## 🔍 SQL Analysis

The SQL analysis focuses on the following business areas:

| Theme | Example Business Questions |
|---|---|
| **A. Sales & Revenue** | What is the total revenue? Which months generate the highest revenue? |
| **B. Product Analysis** | Which products and categories generate the most revenue? |
| **C. Profitability Analysis** | Which products have the highest profit and profit margins? |
| **D. Customer Analysis** | Who are the top customers? What is the repeat purchase rate? |
| **E. Regional Analysis** | Which states contribute the most to total revenue? |
| **F. Payment & Orders** | Which payment methods are popular? What is the order status distribution? |
| **G. Acquisition Analysis** | Which customer acquisition channels contribute to purchases? |
| **H. Discount Analysis** | How do discounts affect revenue and profitability? |

---

## 📊 Power BI Dashboard

The Power BI dashboard provides an interactive overview of e-commerce sales performance through KPIs, visualizations, and filters.

### Dashboard Preview

![E-commerce Retail Sales Analysis Dashboard](screenshots/dashboard.png)

### Key Performance Indicators (KPIs)

- Total Revenue
- Total Profit
- Total Orders
- Average Order Value (AOV)
- Repeat Purchase Rate

### Dashboard Visualizations

1. Monthly Revenue Trend
2. Revenue by Category
3. Top 10 Products by Revenue
4. Revenue by State
5. Payment Method Distribution
6. Product Profit Margin
7. Customer Acquisition Channel

### Interactive Filters

- Order Date
- Category
- State
- Payment Method

The dashboard allows users to explore business performance across different dimensions and identify important sales patterns.

---

## 📈 Key Business Insights

The analysis focuses on identifying:

- Revenue trends and changes over time.
- Products and categories contributing the most to sales.
- Products generating higher profit margins.
- States contributing significantly to revenue.
- Customer repeat purchasing behaviour.
- Popular payment methods.
- Customer acquisition channels contributing to purchases.
- Opportunities to improve sales and profitability.

---

## 🗂️ Repository Structure

```text
Ecommerce-Retail-Sales-Analysis/
│
├── data/
│   ├── cleaned_customers.csv
│   ├── cleaned_orders.csv
│   ├── cleaned_products.csv
│   └── cleaned_order_items.csv
│
├── Python/
│   └── data_cleaning_analysis.ipynb
│
├── SQL/
│   └── sales_analysis.sql
│
├── PowerBI/
│   └── Ecommerce_Retail_Sales_Analysis.pbix
│
├── screenshots/
│   └── dashboard.png
│
└── README.md
```

*Update the filenames to match your actual uploaded files. Do not upload confidential or sensitive customer information.*

---

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/TharunKumar1111/Ecommerce-Retail-Sales-Analysis.git
cd Ecommerce-Retail-Sales-Analysis
```

### 2. Python Analysis

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

Open the Python notebook and update the dataset paths if necessary.

### 3. SQL Analysis

- Create a database in MySQL.
- Import the required datasets into their respective tables.
- Open the SQL analysis file.
- Execute the queries to explore business performance.

### 4. Power BI Dashboard

- Open the `.pbix` file using Power BI Desktop.
- Refresh the data if required.
- Update the data source paths if prompted.
- Explore the dashboard using the available slicers.

---

## 🚀 Future Development – Machine Learning

The next phase of this project will focus on integrating Machine Learning techniques to move beyond descriptive analytics and generate predictive business insights.

Planned enhancements:

- **Sales Forecasting:** Predict future revenue using historical sales data.
- **Customer Segmentation:** Group customers based on purchasing behaviour using K-Means clustering.
- **Repeat Purchase Prediction:** Predict the likelihood of customers making repeat purchases.
- **Product Demand Forecasting:** Estimate future product demand to support inventory planning.
- **Profit Prediction:** Develop models to estimate future product profitability.

**Planned Technologies:** Python, Pandas, NumPy, Scikit-learn, and Matplotlib.

---

## 👤 Author

**Tharun Kumar Reddy**

Computer Science Engineering Student

**Project:** E-commerce Retail Sales Analysis

---

⭐ If you find this project useful, consider giving the repository a star!
