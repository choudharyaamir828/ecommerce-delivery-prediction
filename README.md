# 🛍️ E-commerce Delivery Prediction & Sales Insights

This project combines **business intelligence** and **machine learning** to analyze customer behavior and predict delivery outcomes for an online store with over **650,000 transactions**. It provides actionable recommendations to improve sales and demonstrates the use of **CatBoost**, a powerful algorithm for categorical data.

---

## 📊 Business Insights from Data Analysis

Using Excel and Python, the following key patterns were identified:

- **👩 Gender Trends:**  
  Women are significantly more likely to purchase than men, contributing approximately **69%** of total orders.

- **📍 Top Performing States:**  
  The highest sales volume comes from **Maharashtra**, **Karnataka**, and **Uttar Pradesh**.

- **🎯 Age Group Contribution:**  
  Adults aged **30–49 years** account for nearly **50%** of all purchases.

- **🛒 Dominant Sales Channels:**  
  **Amazon**, **Flipkart**, and **Myntra** together drive around **80%** of total sales.

### 📈 Strategic Recommendation

To boost sales, target **women aged 30–49** in the top three states with **ads, offers, and coupons** on **Amazon, Flipkart, and Myntra**.

---

## 🤖 Machine Learning: Delivery Status Prediction

### 🎯 Objective

Predict whether a product will be **delivered** or **not delivered** based on order details.

### 🧠 Algorithm Used

**CatBoost Classifier** — chosen for its superior handling of categorical features and high performance.

### 📊 Model Performance

- **Accuracy:** ~90% on validation data
- **Robustness:** Handles categorical variables without extensive preprocessing

### 📥 Features Used

```python
['Gender', 'Age', 'Channel', 'SKU', 'Category', 'Size', 'Qty', 'Amount',
 'ship-city', 'ship-state', 'B2B', 'order_day', 'order_month', 'order_weekday']


---

## 🚀 How to Run

### 1. Install dependencies
```bash
pip install -r requirements.txt

<img width="1855" height="725" alt="final" src="https://github.com/user-attachments/assets/b5ba41a4-fbb6-420b-b1c3-e2c865d93bed" />

