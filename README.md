# 📊 Data Analytics Project

## Overview

This project demonstrates an end-to-end **Data Analytics workflow**, starting from raw dataset loading and exploration to SQL analysis, Power BI dashboard development, report generation, and presentation.

The objective is to transform raw data into meaningful business insights using **Python, SQL, and Power BI**.

---

## 📁 Dataset

The project uses a structured dataset containing business-related records for analysis.

The dataset was:

* Loaded and explored using Python
* Checked for missing and duplicate values
* Cleaned and transformed for analysis
* Stored/queried using a relational database
* Used as the source for Power BI visualizations

---

## 🛠️ Tools & Technologies

| Tool                                | Purpose                           |
| ----------------------------------- | --------------------------------- |
| **Python**                          | Data loading, cleaning & EDA      |
| **Pandas**                          | Data manipulation                 |
| **NumPy**                           | Numerical analysis                |
| **Matplotlib / Seaborn**            | Data visualization                |
| **PostgreSQL / MySQL / SQL Server** | SQL analysis & querying           |
| **Power BI**                        | Interactive dashboard             |
| **Gamma**                           | Presentation / PPT creation       |
| **Git & GitHub**                    | Version control & project sharing |

---

## 🔄 Project Workflow

### 1. Load Dataset

The dataset was imported into Python using Pandas.

```python
import pandas as pd

df = pd.read_csv("dataset.csv")

print(df.head())
print(df.shape)
```

### 2. Exploratory Data Analysis (EDA)

Performed EDA to understand the structure and characteristics of the data.

Key activities included:

* Understanding rows and columns
* Checking data types
* Identifying missing values
* Finding duplicate records
* Examining numerical statistics
* Analyzing categorical variables
* Identifying trends and patterns
* Creating exploratory visualizations

---

### 3. Data Cleaning

The dataset was cleaned and prepared for further analysis.

Activities included:

* Handling missing values
* Removing duplicate records
* Correcting data types
* Standardizing column values
* Handling inconsistent data
* Creating derived columns where required

---

### 4. SQL Analysis

The cleaned data was loaded into a relational database and analyzed using SQL.

SQL analysis included:

* Filtering data using `WHERE`
* Aggregations using `SUM`, `AVG`, `COUNT`, etc.
* `GROUP BY` and `HAVING`
* Joins
* Subqueries
* CTEs
* Window functions
* Ranking and trend analysis

Example:

```sql
SELECT
    category,
    SUM(sales) AS total_sales
FROM sales_data
GROUP BY category
ORDER BY total_sales DESC;
```

The queries can be executed using **PostgreSQL, MySQL, or SQL Server**, depending on the database environment used.

---

## 📊 Power BI Dashboard

An interactive Power BI dashboard was created to present the key findings in an easy-to-understand format.

### Dashboard Features

* KPI cards
* Trend analysis
* Category-wise analysis
* Filters and slicers
* Interactive charts
* Drill-down analysis
* Business performance indicators

The dashboard allows users to interact with the data and identify important trends and patterns.

---

## 📈 Results & Insights

The analysis helped identify:

* Key business performance indicators
* Important trends over time
* Top-performing categories/products
* Areas requiring attention
* Relationships between different business dimensions
* Data-driven insights that can support business decisions

Detailed findings are documented in the project report.

---

## 📄 Project Report

A detailed report was prepared covering:

1. Business problem
2. Dataset description
3. Data preparation
4. Exploratory data analysis
5. SQL analysis
6. Power BI dashboard
7. Key insights
8. Business recommendations

---

## 🎯 Presentation

A professional presentation was created using **Gamma** to summarize the project.

The presentation includes:

* Project objective
* Dataset overview
* Methodology
* EDA findings
* SQL analysis
* Power BI dashboard
* Key insights
* Recommendations
* Conclusion

---

## 📂 Project Structure

```text
Data-Analytics-Project/
│
├── data/
│   └── dataset.csv
│
├── python/
│   └── EDA_and_Cleaning.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── powerbi/
│   └── dashboard.pbix
│
├── report/
│   └── project_report.pdf
│
├── presentation/
│   └── project_presentation.pdf
│
└── README.md
```

---

## ▶️ How to Run

### Step 1: Clone the Repository

```bash
git clone <repository-url>
```

### Step 2: Navigate to the Project

```bash
cd Data-Analytics-Project
```

### Step 3: Install Python Libraries

```bash
pip install pandas numpy matplotlib seaborn
```

### Step 4: Run the Python Analysis

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Run the EDA and data-cleaning notebook.

### Step 5: Set Up the Database

Create a database in **PostgreSQL, MySQL, or SQL Server** and load the cleaned dataset.

Execute the SQL scripts available in:

```text
sql/analysis_queries.sql
```

### Step 6: Open the Power BI Dashboard

Open the `.pbix` file using **Power BI Desktop**.

Update the database connection if required and refresh the data.

---

## 👨‍💻 Skills Demonstrated

* Python
* Pandas
* Exploratory Data Analysis
* Data Cleaning
* SQL
* PostgreSQL / MySQL / SQL Server
* Data Analysis
* Power BI
* Data Visualization
* Business Intelligence
* Report Writing
* Data Storytelling
* Git & GitHub

---

## 📌 Conclusion

This project demonstrates an end-to-end approach to solving a data analytics problem — from **raw data to actionable business insights**.

It combines Python-based analysis, SQL querying, Power BI visualization, and business reporting to create a complete analytics solution.

