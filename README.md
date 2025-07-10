# 🛒 Walmart Sales Data Analysis & Visualization

A complete end-to-end data analysis project using Python, Pandas, MySQL (MariaDB), and Matplotlib/Seaborn. This project focuses on cleaning, analyzing, and visualizing retail sales data from a Walmart dataset to extract business insights.

---

## 📁 Dataset

The dataset contains transactional sales data with the following features:

- Invoice ID
- Branch, City
- Category (product type)
- Unit Price, Quantity
- Date, Time
- Payment Method
- Customer Rating
- Profit Margin

> ✅ Cleaned version used: `walmart_cleaned.csv`

---

## 🎯 Objectives

- Preprocess and clean real-world transactional data
- Perform feature engineering and transformation
- Conduct trend and performance analysis
- Visualize insights through clear, readable plots

---

## 🔧 Tools & Technologies

- Python (Pandas, NumPy)
- MySQL / MariaDB
- Matplotlib & Seaborn
- Jupyter Notebook
- Plotly (optional for interactive graphs)

---

## 🔬 Feature Engineering

- Parsed `Time` and `Date` into `Hour`, `Time Slot`, and `Day`
- Calculated `Total_Amount = Unit_Price × Quantity`
- Converted time formats and removed currency symbols
- Handled missing and duplicate values

---

## 📊 Trend & Performance Analysis

### 1. Revenue Trends
- By Branch & Category (Heatmaps, Bar Charts)

### 2. Best-Selling Categories
- Quantity-wise & Revenue-wise breakdown

### 3. Sales Patterns
- Across Time of Day (Morning, Afternoon, Evening, Night)
- By Payment Method and City

### 4. Peak Sales Hours
- Line plots for hourly trends

### 5. Profit Margin Analysis
- By Branch & Category using Faceted Bar Charts

---

## 📈 Visual Examples

*(Screenshots or saved PNG plots can be added here)*

---

## 🧹 Data Cleaning Highlights

- Removed rows with missing `Unit_Price` or `Quantity`
- Converted `Unit_Price` from string to float
- Transformed `Time` from timedelta to HH:MM:SS format
- Parsed and validated date-time fields
- Ensured consistency in categorical values

---

## 📂 Project Structure
├── EADME.md
├── Walmart.csv
├── project.ipynb
└── walmart_cleaned.csv

