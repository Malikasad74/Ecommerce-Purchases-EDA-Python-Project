# 🛒 Ecommerce Purchases – Exploratory Data Analysis (EDA)

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange)
![EDA](https://img.shields.io/badge/Project-EDA-success)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on an e-commerce purchases dataset to uncover:

- Customer purchase behavior
- Payment trends
- Time-based buying patterns
- Email domain popularity
- Credit card usage insights

The goal is to simulate a **real-world business analytics scenario** using Python and Pandas.

---

## 🎯 Business Questions Solved

✔ What is the average purchase price?  
✔ Which payment providers are most used?  
✔ Do customers purchase more in AM or PM?  
✔ Which email providers dominate the customer base?  
✔ How many technical professionals (Engineers) are customers?  

---

## 📊 Dataset Information

| Feature | Details |
|---|---|
| Rows | 10,000 |
| Columns | 14 |
| Missing Values | None |
| Memory Usage | ~1.1 MB |

### 🧾 Columns Included
- Address
- Lot
- AM or PM
- Browser Info
- Company
- Credit Card
- CC Exp Date
- CC Security Code
- CC Provider
- Email
- Job
- IP Address
- Language
- Purchase Price

---

## 🧰 Tech Stack

- 🐍 Python
- 🐼 Pandas
- 📓 Jupyter Notebook

---

## 🔍 Key Analysis Performed

### 📈 Statistical Analysis
- Highest Purchase Price → **$99.99**
- Lowest Purchase Price → **$0.00**
- Average Purchase Price → **$50.35**

---

### 🌍 Customer Language Insights
- French Language Users → **1097 Customers**

---

### 💳 Payment Insights
- Mastercard Purchases > $50 → **405 Customers**
- Credit Cards Expiring in 2020 → **988 Customers**

---

### ⏰ Time-Based Purchase Behavior
| Time | Purchases |
|---|---|
| AM | 4932 |
| PM | 5068 |

➡ Slightly higher purchase activity during **PM**

---

### 📧 Email Provider Popularity
Top Email Domains:

1. hotmail.com
2. yahoo.com
3. gmail.com
4. smith.com
5. williams.com

---

## 🧠 Interesting Insights

📌 Purchases are almost evenly split between AM and PM  
📌 Email usage shows strong dominance of legacy providers (Hotmail, Yahoo)  
📌 Average purchase value is around mid-range → Indicates balanced pricing strategy  

---

## 🧪 Sample Analysis Tasks

✔ Find customers using specific IP address  
✔ Detect job titles containing "Engineer"  
✔ Extract email domains using string operations  
✔ Filter high-value purchases by payment provider  

---

## 📂 Project Structure

📁 Ecommerce-Purchases-EDA
├ 📄 Ecommerce Purchases Dataset.csv
├ 📓 EDA Notebook.ipynb
└ 📄 README.md



---

## 🚀 How to Run

```bash
# Clone repository
git clone https://github.com/Malikasad74/ecommerce-eda.git

# Install dependencies
pip install pandas

# Run notebook
jupyter notebook
