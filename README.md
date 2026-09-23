# 📊 Sales Analytics & Business Intelligence Dashboard

An end-to-end **Sales Analytics and Business Intelligence project** built using **Python, Pandas, SQL, DuckDB, and Power BI** to analyze e-commerce transaction data and generate meaningful business insights.

## 📌 Project Overview

This project analyzes **5,000 e-commerce transactions** to understand:

* Sales and revenue performance
* Product category performance
* Regional sales trends
* Customer purchasing behavior
* Payment method preferences
* Discount patterns
* Delivery performance
* Customer satisfaction

The project combines **Python-based data analysis, SQL business analysis, and Power BI visualization** to transform raw transaction data into meaningful business insights.

## 🎯 Objectives

* Analyze overall sales performance
* Identify high-performing product categories
* Compare regional sales performance
* Understand customer purchasing patterns
* Analyze payment method usage
* Study discount patterns
* Evaluate delivery performance
* Analyze customer satisfaction
* Identify high-value transactions
* Analyze monthly sales trends
* Build an interactive Power BI dashboard
* Generate data-driven business insights

## 🛠️ Technologies & Tools

| Technology   | Purpose                         |
| ------------ | ------------------------------- |
| Python       | Data analysis and preprocessing |
| Pandas       | Data manipulation and cleaning  |
| NumPy        | Numerical analysis              |
| Matplotlib   | Data visualization              |
| Seaborn      | Statistical visualization       |
| SQL          | Business analysis               |
| DuckDB       | SQL analysis in Colab           |
| Power BI     | Interactive dashboard           |
| Google Colab | Development environment         |
| GitHub       | Project documentation           |

## 📂 Dataset

The dataset contains **5,000 e-commerce transactions**.

### Key Features

| Column             | Description             |
| ------------------ | ----------------------- |
| `order_id`         | Unique order identifier |
| `order_date`       | Order date              |
| `customer_id`      | Customer identifier     |
| `product_category` | Product category        |
| `region`           | Sales region            |
| `quantity`         | Quantity purchased      |
| `unit_price`       | Price per unit          |
| `discount`         | Discount applied        |
| `payment_method`   | Payment method          |
| `delivery_days`    | Delivery duration       |
| `customer_rating`  | Customer rating         |
| `revenue`          | Revenue generated       |

## 🔄 Project Workflow

```text
Data Collection
      ↓
Data Cleaning
      ↓
Data Validation
      ↓
Feature Engineering
      ↓
Exploratory Data Analysis
      ↓
KPI Analysis
      ↓
SQL Business Analysis
      ↓
Data Visualization
      ↓
Power BI Dashboard
      ↓
Business Insights
```

## 🧹 Data Preparation

Data preprocessing and validation were performed using **Python and Pandas**.

* Checked missing values
* Checked duplicate records
* Verified data types
* Converted `order_date` into datetime format
* Validated numerical columns
* Checked categorical values
* Prepared dashboard-ready data

## ⚙️ Feature Engineering

Created additional analytical features including:

* `year`
* `month`
* `month_name`
* `day`
* `day_name`
* `gross_sales`
* `discount_amount`
* `net_sales`

These features were used for **time-based analysis, KPI calculations, and business reporting**.

## 📊 Exploratory Data Analysis

EDA was performed to identify patterns and trends across:

* Product categories
* Regions
* Payment methods
* Monthly sales
* Customer behavior
* Quantity purchased
* Delivery time
* Customer ratings
* Discount rates

Visualizations were created using **Matplotlib and Seaborn**.

## 📈 KPI Analysis

Key business metrics analyzed include:

* **Total Revenue**
* **Total Orders**
* **Total Quantity Sold**
* **Average Order Value**
* **Average Customer Rating**
* **Revenue by Category**
* **Revenue by Region**
* **Monthly Revenue Trend**

### Average Order Value

```text
Average Order Value = Total Revenue / Total Orders
```

## 🗄️ SQL Business Analysis

Used **DuckDB SQL** to perform business-oriented analysis such as:

* Revenue by product category
* Revenue by region
* Monthly sales trends
* Payment method analysis
* Customer purchase analysis
* High-value transactions
* Category-wise quantity analysis
* Business KPI calculations

### Example SQL Query

```sql
SELECT
    product_category,
    SUM(revenue) AS total_revenue
FROM sales
GROUP BY product_category
ORDER BY total_revenue DESC;
```

## 📊 Power BI Dashboard

An interactive **Power BI dashboard** was created to monitor sales performance.

### KPI Cards

* 💰 Total Revenue
* 🛒 Total Orders
* 📦 Total Quantity
* 📊 Average Order Value
* ⭐ Average Customer Rating

### Visualizations

* Revenue by Product Category
* Revenue by Region
* Monthly Revenue Trend
* Payment Method Distribution
* Quantity by Category
* Customer Rating Analysis
* Delivery Performance Analysis

### Filters / Slicers

* Year
* Product Category
* Region
* Payment Method

## 💡 Business Insights

The analysis helps identify:

* Which product categories generate higher revenue
* Which regions contribute more to sales
* How sales change over time
* Customer payment preferences
* Customer purchasing patterns
* Discount patterns and their relationship with sales
* Delivery performance
* Customer satisfaction trends
* High-value transactions

## 📁 Project Structure

```text
Sales-Analytics-Business-Intelligence-Dashboard/
│
├── README.md
├── ecommerce_sales_dashboard.csv
├── Sales_Analytics.ipynb
│
└── dashboard/
    └── PowerBI_Dashboard.pbix
```

## ▶️ How to Run

### 1. Open Google Colab

Open the `Sales_Analytics.ipynb` notebook in Google Colab.

### 2. Install Required Libraries

```python
!pip install pandas numpy matplotlib seaborn duckdb
```

### 3. Load the Dataset

Load:

```text
ecommerce_sales_dashboard.csv
```

into the Colab environment.

### 4. Run the Notebook

Execute the notebook cells sequentially to perform:

```text
Data Loading
      ↓
Data Cleaning
      ↓
Feature Engineering
      ↓
EDA
      ↓
KPI Analysis
      ↓
SQL Analysis
      ↓
Visualization
```

### 5. Open Power BI Dashboard

Open:

```text
dashboard/PowerBI_Dashboard.pbix
```

using **Microsoft Power BI Desktop**.

## 🧠 Skills Demonstrated

### Data Analytics

* Data Cleaning
* Data Validation
* Exploratory Data Analysis
* Feature Engineering
* KPI Analysis
* Business Analytics
* Data Interpretation

### Python

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

### SQL & Business Intelligence

* SQL
* DuckDB
* Aggregations
* GROUP BY
* ORDER BY
* Business Queries
* Power BI
* Dashboard Development
* Data Visualization

## 🚀 Project Outcome

This project demonstrates an end-to-end **Data Analytics and Business Intelligence workflow**, transforming raw e-commerce transaction data into structured analysis and interactive Power BI reporting.

**Python → Data Cleaning → EDA → Feature Engineering → SQL → KPI Analysis → Visualization → Power BI → Business Insights**

## 👩‍💻 Author

**Aparna Pandey**

B.Tech — Computer Science & Engineering
Specialization: Artificial Intelligence & Machine Learning

GitHub: **aparnapandey26**

---

⭐ **If you find this project useful, feel free to explore the notebook and dashboard.**
