# 📊 Income Inequality Analysis using IRS SOI Data

## 📌 Project Overview
This project focuses on analyzing income distribution and measuring economic inequality using the IRS Statistics of Income (SOI) dataset. The analysis is performed using Python with statistical and visualization techniques.

---

## 🎯 Objective
- To study income distribution across ZIP codes and income groups  
- To measure inequality using statistical indicators  
- To visualize income patterns and disparities  

---

## 📂 Dataset
- Source: IRS Statistics of Income (SOI)
- Type: ZIP Code Level Aggregated Data  
- Key Features:
  - Adjusted Gross Income (A00100)
  - Number of Returns (N1)
  - Income Groups (agi_stub)
  - State and ZIP Code  

---

## ⚙️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- SciPy  

---

## 🔍 Project Workflow

### 1. Data Cleaning
- Handled missing values  
- Selected relevant columns  
- Removed invalid entries  

### 2. Feature Engineering
- Calculated average income per return  

### 3. Exploratory Data Analysis
- Income distribution plots  
- AGI group comparison  
- State-wise analysis  

### 4. Statistical Modeling
- Log transformation of income  
- Distribution fitting  

### 5. Inequality Measurement
- Gini Coefficient  
- Lorenz Curve  

---

## 📊 Key Insights
- Income distribution is highly skewed  
- Higher income groups dominate total income  
- Inequality exists across regions  
- Log transformation improves data interpretation  

---

## 🧾 Conclusion
The project highlights significant income inequality using IRS SOI data. Statistical analysis and visualization confirm that income is unevenly distributed, with a concentration in higher income groups.

---

## 📁 Project Structure
income-inequality-soi-analysis/
│
├── data/
├── notebook/
├── report/
└── README.md
