# MIS-311
# 🌍 Cost of Living and Income Analysis

This project performs **Exploratory Data Analysis (EDA)** on a global dataset comparing **Average Monthly Income** and **Cost of Living** across multiple countries and regions. The goal is to understand global economic differences, detect patterns, and highlight insights about affordability and income distribution.

---

## 📄 Data Overview

**Rows:** 202  
**Columns:** 5  
**Features:**
- **Country** – Name of the country  
- **Region** – Geographical region of the country  
- **Year** – Year when the data was recorded  
- **Average_Monthly_Income** – Average monthly income of individuals (USD)  
- **Cost_of_Living** – Average monthly cost of living including essentials like housing, food, and utilities (USD)

**Context:**  
This dataset helps analyze the relationship between income and living costs across the world — useful for understanding global affordability and income inequality.

---

## 🧹 Data Cleaning

- **Missing Values:**
  - `Average_Monthly_Income`: 2 missing → handled using the **median income** of the same region or global median.
  - `Region`: 2 missing → filled based on **country name**.

- **Duplicate Rows:**  
  - Found **2 duplicates** → removed using Excel’s “Remove Duplicates” feature.

---

## 📊 Descriptive Statistics

| Metric | Average Monthly Income (USD) | Cost of Living (USD) |
|--------|------------------------------|----------------------|
| **Mean** | 4,244 | 3,705 |
| **Standard Deviation** | 2,116.64 | 1,982.22 |

Both variables show high variation, reflecting economic inequality — some countries have comfortable income-to-cost ratios, while others face financial strain due to lower incomes or higher expenses.

---

## 💡 Insights

### 1️⃣ Relationship Between Income and Cost of Living
The scatter plot shows little-to-no relationship between *Average Monthly Income* and *Cost of Living*. Countries with high incomes do not always have high expenses, suggesting other factors like **economic structure**, **regional prices**, or **currency strength** influence living costs more strongly.

### 2️⃣ Income Distribution
The histogram shows that most countries have average monthly incomes between **$3,000 and $4,500**, with fewer at the very high or low ends. This indicates a **moderate concentration** of income levels globally and **limited extreme disparities**.

### 3️⃣ Cost of Living Distribution
Most countries have a cost of living between **$4,000 and $5,000**, with few outliers on either side. This suggests that while expenses vary, they remain **relatively balanced** across most nations.

---

## 🧠 Key Takeaways
- The relationship between income and cost of living is **weak**, implying local factors shape affordability more than income levels.  
- Both income and living costs show **wide variation**, highlighting global economic inequality.  
- Most countries fall into a **moderate range** of income and living expenses, showing some economic balance globally.

---

## 🛠 Tools Used
- **Excel** for data cleaning, visualization, and descriptive analysis  
- **Python (optional)** for extended data exploration and reproducibility  
- **Matplotlib & Seaborn** for additional visualizations (if coded)

---

## 📁 File Information
**Dataset:** `01_Cost of Living.xlsx`  
**Author:** Yeeted Lê  
**Course:** Business Analytics – Data Homework 311  
**Date:** November 2025  

---

### 🖋️ License
This project is open for educational use. You may use, modify, and share it with proper attribution.
