# 📊 Customer Shopping Trends & Behavior Analysis

An end-to-end corporate-grade data analytics project leveraging **Python (Pandas, Scikit-Learn)**, **SQL (PostgreSQL / MySQL)**, and **Power BI** to uncover key consumer shopping patterns, customer segmentation, discount sensitivity, and revenue drivers.

---

## 📌 Executive Summary

Modern retail organizations rely heavily on data-driven strategies to maximize customer retention and lifetime value. This project analyzes customer transactions across 3,900+ retail purchase records to address critical business questions:

- **Customer Segmentation**: Differentiating purchase behavior between Subscribers vs. Non-Subscribers and Loyal vs. New buyers.
- **Revenue Drivers**: Evaluating category performance, shipping preference impact, and age group revenue contributions.
- **Promotions & Discounts**: Assessing whether discounts drive higher cart totals or compress profit margins.

---

## 🛠️ Project Architecture & Tech Stack

```
 Raw Data (CSV)
      │
      ▼
 🐍 Python (Pandas) ────► Data Cleaning, Imputation & Feature Engineering
      │
      ▼
 🛢️ SQL Database ──────► PostgreSQL / MySQL Transactions & Advanced Querying
      │
      ▼
 📊 Power BI ──────────► Interactive Executive Dashboard & KPI Metrics
```

| Technology | Purpose |
| :--- | :--- |
| **Python 3.9+** | Data Wrangling, Missing Value Imputation, Categorical Feature Engineering |
| **PostgreSQL / MySQL** | Relational Data Storage, CTEs, Window Functions (`NTILE`, `DENSE_RANK`) |
| **Power BI** | Dynamic Dashboards, DAX Measures, Visual Storytelling |
| **Jupyter Notebook** | Interactive Exploratory Data Analysis (EDA) Workflow |

---

## 📂 Repository Structure

```
├── customer_shopping_behavior.csv         # Raw retail dataset (3,900 records)
├── Customer_Shopping_Behavior_Analysis.ipynb # Data cleaning, transformation & DB load script
├── customer_behavior_sql_queries.sql      # 15 business queries (Basic + Advanced Window Functions)
├── customer_behavior_dashboard.pbix       # Power BI Interactive Dashboard
├── Customer-Shopping-Behavior-Analysis.pptx # Stakeholder Presentation Deck
├── Business Problem Document.pdf          # Detailed project specification document
├── requirements.txt                       # Python dependencies
└── LICENSE                                # MIT License
```

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/Adityatomar28/customer-shopping-trends-analysis.git
cd customer-shopping-trends-analysis
```

### 2. Set Up Environment & Install Dependencies
```bash
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

### 3. Run Data Cleaning & Database Migration
1. Open and run `Customer_Shopping_Behavior_Analysis.ipynb` using Jupyter Notebook.
2. The notebook cleans missing ratings, transforms column formats, creates age groups, and exports the data directly into your local SQL database (`customer_behavior`).

### 4. Execute SQL Queries
1. Open `customer_behavior_sql_queries.sql` in **pgAdmin**, **MySQL Workbench**, or **DBeaver**.
2. Run queries Q1 to Q15 to extract key business insights.

---

## 💡 Key Business Insights

1. **Subscription Impact**: Subscription status strongly correlates with repeat purchase frequency, but non-subscribers still contribute significant top-line revenue.
2. **Age Group Dynamics**: Middle-aged and Senior demographics generate a higher average purchase value compared to younger segments.
3. **Discount Usage**: Over 50% of discounted orders exceed the average purchase threshold, proving promotional codes effectively boost basket size.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE) - feel free to fork, customize, and use it in your own portfolio.

---

## 👤 Author

**Aditya Tomar**

- 📁 **GitHub**: [@Adityatomar28](https://github.com/Adityatomar28)
