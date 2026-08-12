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

## 📊 Dataset Columns

The dataset contains restaurant-related information such as:

| Column           | Description                  |
| ---------------- | ---------------------------- |
| `OrderId`        | Unique order identifier      |
| `RestaurantName` | Name of restaurant           |
| `RestaurantType` | Type of restaurant           |
| `Rating`         | Restaurant rating            |
| `No_of_Rating`   | Number of ratings            |
| `AverageCost`    | Average cost                 |
| `OnlineOrder`    | Online ordering availability |
| `TableBooking`   | Table booking availability   |
| `CuisinesType`   | Cuisine type                 |
| `Area`           | Restaurant area              |
| `LocalAddress`   | Local address                |
| `Delivery_time`  | Delivery time in minutes     |

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

## 📈 Exploratory Data Analysis

### 1. Top 10 Restaurant Types

Analyzed the number of restaurants for each restaurant type and visualized the top 10 restaurant types using a bar chart.

### 2. Online Ordering Analysis

Compared restaurant types based on:

* Restaurants offering online orders
* Restaurants without online orders

### 3. Delivery Time by Area

Analyzed the **top 10 areas with the highest average delivery time**.

### 4. Delivery Time by Restaurant Type

Calculated the average delivery time for different restaurant types.

### 5. Fastest and Slowest Cuisine Types

Identified:

* 5 fastest cuisine types
* 5 slowest cuisine types

based on average delivery time.

### 6. Delivery Time Range Analysis

Delivery time was divided into ranges:

* 0–20 minutes
* 21–30 minutes
* 31–40 minutes
* 41–50 minutes
* 51–60 minutes
* 60+ minutes

This helps understand the overall distribution of restaurant delivery times.

### 7. Delivery Time Distribution

A histogram was used to understand the distribution of delivery times.

---

## 📊 Relationship Analysis

### Restaurant Rating vs Delivery Time

A scatter plot was created to investigate whether higher restaurant ratings are associated with faster delivery.

### Average Cost vs Delivery Time

A scatter plot was used to analyze whether restaurant average cost affects delivery time.

**Insight:** The analysis shows no strong visible relationship between average cost and delivery time. Higher-cost restaurants do not necessarily have faster or slower delivery.

### Number of Ratings vs Delivery Time

A scatter plot was created to analyze whether the number of restaurant ratings is related to delivery time.

### Online Ordering vs Delivery Time

Average delivery time was compared between restaurants with and without online ordering.

### Long Delivery Time Analysis

Restaurants with delivery time greater than **45 minutes** were filtered to identify the top areas having restaurants with long delivery times.

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
```

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
```

### 2. Open the project

Open:

```text
Project_jomato.ipynb
```

in Jupyter Notebook or JupyterLab.

### 3. Install required libraries

```bash
pip install pandas matplotlib sqlalchemy pyodbc
```

### 4. Configure SQL Server

The notebook loads the Zomato data from SQL Server using SQLAlchemy.

Update the database connection according to your SQL Server configuration before running the notebook.

---

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

---

## 👨‍💻 Author

**Tinku Payal**

**Data Analyst | Python | SQL | Excel | Power BI**
