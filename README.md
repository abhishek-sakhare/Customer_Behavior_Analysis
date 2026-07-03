# Customer Shopping Behavior Analysis

An end-to-end Data Analytics project that analyzes customer shopping behavior using **Python, MySQL, SQL, and Power BI** to uncover purchasing trends, customer segments, and business insights that help improve marketing strategies and customer engagement.

---

## Business Problem

A leading retail company wants to understand customer purchasing behavior across demographics, product categories, and shopping channels. The objective is to identify factors influencing buying decisions, improve customer retention, and optimize marketing strategies through data-driven insights.

---

## Project Overview

This project analyzes a retail dataset containing **3,900 customer transactions** and transforms raw data into actionable business insights through:

-  Data Cleaning & Preprocessing (Python)
-  Database Management & Business Analysis (MySQL + SQL)
-  Interactive Dashboard Development (Power BI)
-  Business Recommendations

---

##  Tech Stack

- **Python**
  - Pandas
  - NumPy
  - SQLAlchemy
- **PostgreSQL**
- **SQL**
- **Power BI**
- **Git & GitHub**

---

##  Project Structure

```
Customer-Shopping-Behavior-Analysis/
│
├── dataset/
│   └── shopping_trends.csv
│
├── python/
│   ├── data_cleaning.py
│   ├── preprocessing.py
│   └── database_upload.py
│
├── sql/
│   ├── schema.sql
│   ├── queries.sql
│   └── business_analysis.sql
│
├── powerbi/
│   └── Customer_Behavior_Dashboard.pbix
│
├── report/
│   └── Project_Report.pdf
│
├── images/
│   └── dashboard.png
│
└── README.md
```

---

##  Dataset Information

- **Total Records:** 3,900
- **Features:** 18

### Dataset Includes

- Customer Demographics
- Product Categories
- Purchase Amount
- Discounts
- Review Ratings
- Shipping Types
- Subscription Status
- Purchase Frequency
- Seasonal Trends

---

##  Data Preprocessing

The dataset was cleaned and transformed using Python.

### Tasks Performed

- Removed missing values
- Imputed missing review ratings using category-wise median
- Renamed columns using snake_case
- Created Age Groups
- Created Purchase Frequency feature
- Removed redundant columns
- Uploaded cleaned data into MySQL

---

##  SQL Business Analysis

Business queries were written in PostgreSQL to answer key business questions.

### Analysis Performed

- Revenue by Gender
- High Spending Customers using Discounts
- Top Rated Products
- Shipping Type Comparison
- Subscriber vs Non-Subscriber Analysis
- Discount Dependent Products
- Customer Segmentation
- Top Products by Category
- Repeat Buyer Analysis
- Revenue by Age Group

---

## 📈 Power BI Dashboard

Interactive dashboard developed to visualize business insights.

### Dashboard Features

- KPI Cards
  - Total Customers
  - Average Purchase Amount
  - Average Review Rating

- Revenue Analysis
- Sales by Category
- Revenue by Age Group
- Subscription Analysis
- Interactive Filters
  - Gender
  - Category
  - Shipping Type
  - Subscription Status

---

## 💡 Key Business Insights

- Clothing category generated the highest revenue.
- Young adults contributed the highest overall revenue.
- Express shipping customers spent slightly more on average.
- Loyal customers formed the largest customer segment.
- Some products relied heavily on discounts for sales.
- Subscribers represented a smaller customer base but offered opportunities for retention and loyalty programs.

---

## 📌 Business Recommendations

- Introduce attractive subscription benefits.
- Reward repeat customers through loyalty programs.
- Optimize discount strategies to protect profit margins.
- Promote top-rated products through targeted marketing campaigns.
- Focus marketing efforts on high-value customer segments.

---

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/abhishek-sakhare/Customer-Shopping-Behavior-Analysis.git
```

### 2. Install Dependencies

```bash
!pip install pymysql sqlalchemy
```

### 3. Run Data Cleaning

```bash
python data_cleaning.py
```

### 4. Import Data into PostgreSQL

Execute the SQL scripts inside the `sql/` folder.

### 5. Open Power BI Dashboard

Open the `.pbix` file using Power BI Desktop.

---

## 📷 Dashboard Preview

<img width="1918" height="1078" alt="image" src="https://github.com/user-attachments/assets/24c2011c-5d89-431b-815b-e3c1ef0ef1a0" />


## Project Outcomes

- Cleaned and transformed retail transaction data
- Built a MySQL database for analysis
- Solved business problems using SQL
- Created an interactive Power BI dashboard
- Generated actionable business recommendations

---

## Author

**Abhishek Sakhare**

- GitHub: https://github.com//abhishek-sakhare
- LinkedIn: https://linkedin.com/in/abhishek-sakhare-61ab71214

---

## ⭐ If you found this project helpful, consider giving it a Star!
