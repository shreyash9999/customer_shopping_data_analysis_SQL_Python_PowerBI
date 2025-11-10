## 🧾 **README.md**

# 🛒 Customer Behavior Analysis — End-to-End Data Analytics Project

### 📌 Overview

This project demonstrates a **complete data analytics workflow** — from raw data in **MySQL**, analysis & preprocessing in **Python (Jupyter Notebook)**, to dynamic dashboards in **Power BI**.
The goal is to analyze **customer purchase patterns, review behavior, and segmentation** to uncover insights that can improve business strategy and customer retention.

---

## 📂 **Project Files**

| File                                           | Description                                                                                           |
| ---------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| **Business Problem Document.pdf**              | Defines the project objectives, KPIs, and expected insights.                                          |
| **Customer_Behaviour.sql**                     | SQL script to create and populate the MySQL database (`customer_behavior`).                           |
| **customer_shopping_behavior.csv**             | Main dataset used for analysis and dashboarding.                                                      |
| **CSV from workbench .csv**                    | Additional export from MySQL Workbench for validation.                                                |
| **data_operation.ipynb**                       | Jupyter Notebook containing Python-based data cleaning, EDA, and transformation before visualization. |
| **customer_behavior_dashboard.pbix**           | Power BI dashboard file with visual reports and KPIs.                                                 |
| **customer_behavior_dashboard - Power BI.pdf** | PDF version of the Power BI dashboard for reference and documentation.                                |
| **customer_shopping_behavior.numbers**         | Mac Numbers file with tabular insights or validation summaries.                                       |

---

## ⚙️ **Tech Stack**

* **Database:** MySQL (Workbench)
* **Programming:** Python (Jupyter Notebook)
* **Libraries:** Pandas, Matplotlib, Seaborn, SQLAlchemy
* **Visualization:** Power BI Desktop + Power BI Online Workspace
* **Documentation:** PDF Reports

---

## 🧠 **Project Workflow**

### 🧩 **1. Data Storage (MySQL)**

* Created the `customer_behavior` database using `Customer_Behaviour.sql`.
* Structured tables to store customer purchase history, product reviews, and ratings.

### 🧹 **2. Data Analysis & Cleaning (Python/Jupyter)**

* Connected MySQL to Jupyter using SQLAlchemy.
* Cleaned and transformed data using Pandas:

  * Handled missing values
  * Derived new columns (e.g., `customer_segment`)
  * Converted data types and formatted columns
* Conducted Exploratory Data Analysis (EDA):

  * Purchase frequency
  * Average review rating distribution
  * Category-wise revenue
* Exported final cleaned dataset (`customer_shopping_behavior.csv`) for Power BI visualization.

### 📊 **3. Visualization (Power BI)**

* Imported clean dataset into Power BI.
* Built dynamic visuals:

  * 📈 **Top Products by Rating**
  * 👥 **Customer Segmentation (New / Returning / Loyal)**
  * 💰 **Revenue by Category**
  * 📆 **Sales Trends over Time**
* Added DAX measures for average ratings, total revenue, and customer count.
* Published the dashboard to **Power BI Online Workspace** for sharing.

---

## 🔍 **Key Insights**

* **Loyal customers** drive the majority of repeat purchases.
* **Top-rated items** correlate strongly with higher purchase frequency.
* **Seasonal spikes** in sales observed during festive periods.
* **Returning customers** contribute steady monthly revenue.

---

