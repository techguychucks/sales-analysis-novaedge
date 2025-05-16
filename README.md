# 📊 Sales Analysis – NovaEdge Distributors Ltd.

## 🧠 Project Overview

This project analyzes sales data for **NovaEdge Distributors Ltd.** over a 12-month period in 2023. It evaluates revenue distribution by region, product performance, and monthly sales trends using Python and Excel. The goal is to support performance evaluation and strategic decision-making.

---

## 📚 Table of Contents

1. [Data Sources](#data-sources)  
2. [Tools](#tools)  
3. [Data Cleaning / Preparation](#data-cleaning--preparation)  
4. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)  
5. [Data Analysis](#data-analysis)  
6. [Result / Findings](#result--findings)  
7. [Recommendations](#recommendations)  
8. [Limitations](#limitations)  
9. [References](#references)  
10. [Sources](#sources)

---

## 📦 Data Sources

- `sales_data.xlsx`: Contains monthly sales records for 2023 including:
  - Date
  - Product
  - Units Sold
  - Region
  - Revenue

---

## 🛠 Tools

- **Excel** – Data input and formatting
- **Python** (Jupyter Notebook)
  - `pandas` – data manipulation
  - `matplotlib` – charts / visualization
  - `seaborn` – charts / visualization

---

## 🧹 Data Cleaning / Preparation

- Converted the `Date` column to `datetime` format
- Created a new `Month` column for monthly aggregation

---

## 📊 Exploratory Data Analysis (EDA)

- Checked for missing values
- Explored sample data with `.head()`
- Confirmed column data types and structure
- Summarized the dataset for initial observations

---

## 📈 Data Analysis

1. **Total Revenue by Region**  
   Aggregated revenue using `groupby` to assess regional performance

2. **Top-Selling Products**  
   Identified based on total `Units Sold`

3. **Monthly Sales Trend**  
   Analyzed using the new `Month` column and visualized trends across the year

---

## 🧾 Result / Findings

- **Region with Highest Revenue**: **East**
- **Top-Selling Product**: **Product C**
- **Sales Trend**: Revenue **increased steadily** from January to December 2023

This analysis provides clear insight into top-performing regions and products.

---

## 💡 Recommendations

- Focus marketing and distribution in the **North region**
- Expand availability of **Product C**, especially in high-performing regions
- Prepare inventory for **continued growth**, as the trend shows increasing sales

---

## ⚠️ Limitations

- Synthetic data was used and may not reflect external market conditions
- The analysis does not include profit margins or customer segmentation

---

## 📚 References

- [Pandas Documentation](https://pandas.pydata.org/)
- [Matplotlib Documentation](https://matplotlib.org/)
- [Seaborn Documentation](https://seaborn.pydata.org/)

---

## 🔗 Sources

- Data created manually in Excel using ChatGPT
- Insights and visuals derived from Python using open-source libraries
