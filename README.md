# 📦 E-Commerce Delivery Delay Analysis

### 🇻🇳 Author: Nguyễn Gia Khiêm  
Aspiring Data Analyst | 3rd-year student in Electronic Physics Technology & Informatics  
📍 Specializing in Python, BI, and E-commerce data analytics  
📫 [LinkedIn](https://www.linkedin.com/in/gia-khiem-nguyen-9610ba187/) | CEFR B2 Certified | SEMI Bootcamp (Singapore)

---

## 📍 Project Overview

This project analyzes delivery delays in a real-world e-commerce setting using the Olist Brazilian E-Commerce dataset.  
The goal is to detect bottlenecks in the delivery pipeline and propose improvements to optimize logistics efficiency.  
It simulates challenges faced by platforms like **Lazada (Alibaba Group)** where delivery speed is critical to customer satisfaction.

---

## 🎯 Objectives

- Identify and quantify delays in order delivery
- Determine high-risk cities and sellers with recurring delay patterns
- Analyze courier performance and its impact on delivery outcomes
- Provide business-oriented recommendations for reducing delays

---

## 📁 Dataset

**Source:** [Olist Brazilian E-Commerce Dataset – Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)  
This dataset includes over 100,000 orders from multiple Brazilian marketplaces with features such as:

- Order timestamps (purchase, approved, delivered)
- Customer & seller locations
- Freight value and payment data
- Product categories and courier info

---

## 🛠️ Tools & Libraries

- **Python**: `pandas`, `numpy`, `datetime`, `matplotlib`, `seaborn`, `plotly`
- **Jupyter Notebook**: Data cleaning, EDA, insight documentation
- **Visualization**: Time plots, heatmaps, bar & box plots
- **Feature Engineering**: `delivery_delay`, `delivery_duration`, delay flags

---

## 🧠 Core Techniques

- Handling missing data and datetime parsing
- Creating new time-based metrics (e.g., estimated vs actual delivery)
- Aggregation by seller location, product category, delivery service
- Outlier detection using box plots
- Data storytelling: visual insights with business focus

---

## 🔍 Key Insights

- 📌 **Sellers in remote cities** have a 3–5 day longer average delivery time  
- 📌 **Certain couriers** consistently underperform across regions  
- 📌 **Expensive shipping** doesn’t correlate with better on-time delivery  
- 📌 **High-return regions** overlap with high-delay regions → potential cause of churn  

---


## 💡 Recommendations

- Build **dynamic routing rules** based on city-level delay trends  
- **Optimize warehouse assignments** for sellers in remote locations  
- Establish **SLA contracts** with couriers based on past delivery performance  
- Use predictive models to **flag high-risk orders** before shipment

---

## 🧩 Future Enhancements

- Integrate **geolocation heatmaps** for better delay visualization  
- Build a **Streamlit dashboard** to interactively explore delay factors  
- Add regression model to **predict delivery time**

---



