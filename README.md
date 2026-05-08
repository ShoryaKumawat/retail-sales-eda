# 🛒 Retail Sales EDA — Superstore Dataset

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4C72B0)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)

## 📌 Project Overview
Exploratory Data Analysis on the Sample Superstore retail dataset to uncover sales trends, 
top performing categories, regional profitability, and the impact of discounts on profit.

## 📁 Dataset
- **Source:** Kaggle — Sample Superstore Dataset
- **Size:** 9,994 rows × 21 columns
- **Features:** Order Date, Sales, Profit, Category, Sub-Category, Region, Discount, Quantity

## 🔧 Tools & Libraries
| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Pandas | Data manipulation & cleaning |
| Matplotlib | Data visualization |
| Seaborn | Statistical plots |
| Jupyter Notebook | Interactive development |

## 📊 Key Steps
1. **Data Loading & Inspection** — shape, dtypes, null checks
2. **Feature Engineering** — extracted Month, Year, Profit Margin
3. **Visualizations** — category sales, seasonal trends, regional profit
4. **Outlier Detection** — IQR method on Sales, Profit, Discount

## 🔍 Key Findings
- 📈 **Technology** is the highest selling category
- 📅 **Sales peak in Q4** (Oct–Dec) every year — strong seasonal pattern
- 🌍 **West region** generates the highest profit
- 💸 **Discounts above 40%** consistently result in losses
- 🚨 **1,167 Sales outliers** and **1,881 Profit outliers** detected and removed

## 📂 Project Structure
