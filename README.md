# 🍽️ Zomato Restaurant Data Analysis

## 📌 Project Overview

This project focuses on **Zomato restaurant data analysis** using Python, Pandas, Matplotlib, and SQL Server.

The main objective is to clean the restaurant dataset and perform **Exploratory Data Analysis (EDA)** to understand restaurant types, online ordering, delivery time, ratings, average cost, cuisine types, and different areas.

---

## 🎯 Project Objectives

* Clean and prepare restaurant data
* Handle missing values
* Check duplicate records
* Analyze restaurant types
* Analyze online ordering availability
* Analyze restaurant delivery time
* Compare delivery time with restaurant rating
* Analyze the relationship between average cost and delivery time
* Analyze delivery time by area, cuisine, and restaurant type
* Identify areas with long delivery times

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **Matplotlib**
* **SQL Server**
* **SQLAlchemy**
* **Jupyter Notebook**

---
## 🔍 Data Cleaning

The following data-cleaning steps were performed:

1. Checked dataset shape using `df.shape`
2. Checked data types using `df.info()`
3. Checked missing values using `df.isnull().sum()`
4. Checked duplicate records
5. Calculated missing-value percentages
6. Checked minimum and maximum values of important numerical columns
7. Filled missing `Rating` values using the **median**
8. Filled missing `AverageCost` values using the **median**
9. Exported the cleaned dataset as `Zomato.csv`

---



## 📌 Key Business Questions

This project answers questions such as:

* Which restaurant types are most common?
* Which restaurant types have the highest online-order availability?
* Which areas have the highest average delivery time?
* Which restaurant types have longer delivery times?
* Which cuisines have the fastest and slowest delivery?
* How are restaurants distributed across delivery-time ranges?
* Does restaurant rating affect delivery time?
* Does average cost affect delivery time?
* Does the number of ratings relate to delivery time?
* Which areas have more restaurants with delivery times above 45 minutes?

---

## 📂 Project Structure

```text
Zomato-Data-Analysis/
│
├── Project_jomato.ipynb
├── Zomato.csv
└── README.md


## 📌 Project Outcome

This project demonstrates practical skills in:

* Data Cleaning
* Exploratory Data Analysis
* Missing Value Handling
* Data Visualization
* GroupBy Analysis
* Business Question Analysis
* SQL Server Integration
* Python Data Analysis
## Understand → Inspect → Clean → Validate → EDA → Visualize → Find Insights → Business Recommendation
---
## recommendation
Based on my analysis, I identified the areas where performance was declining. I recommended focusing on those areas, analyzing the underlying reasons, and taking targeted business actions such as improving promotions, pricing, or customer engagement
## 👨‍💻 Author

**Tinku Payal**

**Data Analyst | Python | SQL | Excel | Power BI**
