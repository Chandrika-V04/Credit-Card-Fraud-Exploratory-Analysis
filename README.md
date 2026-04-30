# Credit-Card-Fraud-Exploratory-Analysis
Comprehensive Exploratory Data Analysis (EDA) of credit card transactions to identify fraud patterns. Features data cleaning, feature engineering (Age derivation), and merchant/category-level fraud trend analysis using Python and Matplotlib.

## 📌 Overview

This project performs **in-depth exploratory data analysis (EDA)** on credit card transactions to uncover **fraud patterns, behavioral trends, and financial anomalies**.

The analysis helps in understanding:
- How fraudulent transactions occur  
- Which categories and merchants are high-risk  
- How fraud varies across regions and transaction amounts

## 🎯 Objectives

- Detect patterns in fraudulent transactions  
- Analyze fraud distribution across multiple dimensions  
- Identify high-risk merchants and categories  
- Generate insights for building fraud detection systems  

---

## 📂 Dataset

The dataset used in this project contains detailed records of credit card transactions, including transaction amount, merchant details, category, location, and fraud labels.

Due to file size limitations, the dataset is not hosted directly in this repository.

---

### 📥 Download Dataset

<p align="center">
  <a href="https://docs.google.com/spreadsheets/d/1E_kGXha3y0vXW9JHRYnBQhI9dqeMxkL8Xi1j6jh9dtE/edit?usp=sharing" >
    <img src="https://img.shields.io/badge/Download-Dataset-blue?style=for-the-badge&logo=google-drive" alt="Download Dataset">
  </a>
</p>

---
### 🔑 Dataset Details

- **Type:** Transactional dataset (each row represents a single transaction)  
- **Format:** `.xlsx`   

---

###  Key Features

- `amt` → Transaction amount  
- `category` → Purchase category  
- `merchant` → Merchant name  
- `state` → Transaction location  
- `dob` → Customer date of birth  
- `is_fraud` → Fraud indicator (0 / 1)  

---

##  Tech Stack

| Category        | Tools Used |
|----------------|----------|
| Language       | Python |
| Data Handling  | Pandas |
| Visualization  | Matplotlib, Seaborn |
| Environment    | Jupyter Notebook / Google Colab |

---

##  Exploratory Data Analysis

###  Data Preprocessing

- Checked missing values and data integrity  
- Converted `dob` into datetime format  
- Created **Age** feature from DOB  
- Verified dataset structure and data types  

---

###  Merchant-Level Fraud Analysis

- Identified merchants with high fraud counts  
- Investigated suspicious merchant activity  
- Highlighted repeatedly flagged merchants  

---

###  Category-Based Fraud Insights

- Analyzed fraud distribution across categories  
- Identified **high-risk spending categories**  
- Compared fraud vs normal transaction patterns  

---

###  Fraud Amount Analysis

- Calculated total fraud amount by:
  - Category  
  - State  
- Identified regions with higher fraud exposure  

---

##  Data Visualization

Clear and insightful visualizations including:

- 📊 Bar charts for fraud counts  
- 🛍️ Category-wise fraud comparisons  
- 🌍 State-wise fraud distribution  

---

##  Key Insights

- Certain categories consistently show higher fraud rates  
- Specific merchants are repeatedly associated with fraud  
- Fraud amounts vary significantly across states  
- Patterns suggest strong potential for predictive modeling  
