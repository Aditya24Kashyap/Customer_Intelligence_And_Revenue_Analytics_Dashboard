# 📊 Customer Intelligence & Revenue Analytics Dashboard

## 🚀 Project Overview

This project presents an end-to-end **Business Intelligence solution** that transforms raw customer transaction data into actionable insights. It demonstrates how businesses can leverage data to understand customer behavior, optimize revenue strategies, and improve retention.

The solution integrates:

* **Python** → Data cleaning & feature engineering
* **SQL** → Business-driven analysis
* **Power BI** → Interactive dashboard & visualization

---

## 🎯 Business Problem

Retail businesses often struggle to understand:

* Which customers generate the most revenue
* Whether discounts actually drive higher spending
* How subscriptions impact long-term customer value
* Which demographics and categories contribute most to growth

### Key Questions:

* Who are the most valuable customers?
* Do discounts increase or reduce revenue?
* Are subscription users more profitable?
* Which age groups and categories drive the most sales?

---

## 🧰 Tech Stack

* **Python (Pandas, NumPy)** – Data preprocessing & feature engineering
* **SQL (PostgreSQL/MySQL)** – Business analysis queries
* **Power BI** – Dashboard & visualization
* **Jupyter Notebook** – Development environment

---

## 📂 Dataset

* ~3,900 customer records
* 18 features including:

  * Demographics (Age, Gender, Location)
  * Purchase behavior (Frequency, Amount)
  * Product details (Category, Item)
  * Customer engagement (Ratings, Subscription Status)

---

## 🔄 Project Workflow

### 1️⃣ Data Preparation (Python)

* Handled missing values (median imputation for ratings)
* Standardized column names
* Removed redundant columns
* Created new features:

  * `age_group`
  * `purchase_frequency_days`

---

### 2️⃣ Feature Engineering

* Segmented customers into:

  * New
  * Returning
  * Loyal
* Converted categorical purchase frequency into numeric values
* Created business-ready structured dataset

---

### 3️⃣ Data Analysis (SQL)

Performed business-focused queries:

* Revenue by gender
* Customer segmentation (New / Returning / Loyal)
* Subscription vs revenue comparison
* Discount impact analysis
* Top products & categories
* Age group revenue contribution

---

### 4️⃣ Dashboard Development (Power BI)

#### 🔝 KPI Cards

* Total Revenue → **$233.1K**
* Total Customers → **4K**
* Average Order Value → **59.76**
* Repeat Customer Rate → **97.87%**
* Average Rating → **3.75**

---

## 📊 Dashboard Insights

### 📌 Revenue Analysis

* Clothing category generates the highest revenue
* Accessories and footwear follow behind

### 👥 Customer Segmentation

* **79% Loyal Customers** → Major revenue drivers
* Returning customers contribute moderate revenue
* New customers are lowest contributors

### 💸 Discount Analysis

* Discounts **do not reduce spending**
* Customers still spend significantly even with promotions

### 🎯 Age Group Insights

* Young Adults & Middle-aged customers drive most revenue
* Seniors contribute relatively less

### 🔁 Subscription Insights

* Subscription users show:

  * Higher engagement
  * More repeat purchases
  * Greater lifetime value

---

## 📈 💼 Business Value Created

This project goes beyond analysis and delivers **actionable business impact**:

* 💰 Identified that **loyal customers contribute ~79% of total revenue**, enabling targeted retention strategies that can significantly increase profitability
* 📊 Demonstrated that **discounts do not reduce spending**, supporting data-driven promotional campaigns without fear of revenue loss
* 🔁 Revealed that **subscription customers have higher repeat purchase rates**, justifying investment in subscription-based business models
* 🎯 Highlighted that **young and middle-aged customers generate the majority of revenue**, enabling focused marketing and customer acquisition strategies
* 🛍️ Discovered top-performing categories, helping optimize **inventory planning and product prioritization**
* 📉 Enabled identification of **low-value customer segments**, supporting cost optimization in marketing spend
* 📦 Provided insights for **customer segmentation (New, Returning, Loyal)** to personalize engagement strategies
* 🚀 Built a scalable framework that allows businesses to **transition from reactive to data-driven decision-making**

---

## 📸 Dashboard Preview

![Dashboard](https://raw.githubusercontent.com/Aditya24Kashyap/Customer_Intelligence_And_Revenue_Analytics_Dashboard/main/Customer%20Intelligence%20And%20Revenue%20Analytics%20Dashboard%20\(1\).png)

---

## 💡 Recommendations

* Focus on **retaining loyal customers** (highest ROI segment)
* Expand and optimize **subscription programs**
* Use **targeted discounts** instead of blanket promotions
* Personalize marketing for high-value segments
* Invest in categories driving maximum revenue

---

## 📁 Project Structure

Customer_Intelligence_And_Revenue_Analytics_Dashboard/
│
├── final_customer_data.csv
├── Customer_Analysis.ipynb
├── Customer_Behavior_SQL_Queries.sql
├── Customer_Intelligence_And_Revenue_Analytics_Dashboard.ipynb
└── README.md

---

## ▶️ How to Run

```bash
git clone <your-repo-link>
cd Customer_Intelligence_And_Revenue_Analytics_Dashboard
```

Open:

* Customer_Analysis.ipynb → Data processing
* Customer_Behavior_SQL_Queries.sql → SQL analysis
* Power BI file → Dashboard visualization

---

## 🎤 Interview-Ready Summary

Built an end-to-end customer intelligence dashboard using Python, SQL, and Power BI that identified high-value customer segments, validated discount effectiveness, and enabled data-driven strategies to improve revenue and customer retention.

---

## 🚀 Future Enhancements

* Real-time data integration
* Machine learning for customer segmentation
* Customer churn prediction
* Recommendation system

---

## 👤 Author

Aditya K
Aspiring Data Analyst / BI Developer
