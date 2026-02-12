# 📦 FedEx Logistics Shipment Analysis (Python EDA)

## 🚀 Project Overview
This project performs an end-to-end Exploratory Data Analysis (EDA) on FedEx logistics shipment data to uncover delivery delays, cost drivers, and operational inefficiencies.

The goal is to answer:
- Why are shipments getting delayed?
- Does higher shipping cost guarantee faster delivery?
- Which vendors and countries cause the most delays?
- How can logistics cost be optimized?

---

## 🎯 Business Problem
FedEx wants to improve logistics efficiency by:
- Reducing delivery delays
- Optimizing freight costs
- Improving vendor performance
- Enabling smarter shipment planning

---

## 📊 Dataset Summary
- **Total Records:** 10,324 shipments
- **Total Features:** 33 columns

Key variables:
- Shipment Mode
- Vendor & Country
- Delivery Dates
- Shipment Weight
- Freight Cost & Insurance
- Product Group
- Line Item Value

---

## 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🔎 Project Workflow

### 1️⃣ Data Cleaning
- Converted date columns to datetime
- Cleaned Freight Cost & Weight columns
- Handled missing values
- Created new features:
  - Delivery Delay
  - Delivery Status

---

### 2️⃣ Exploratory Data Analysis

#### Univariate Analysis
- Shipment mode distribution
- Delivery delay distribution
- Product group distribution

#### Bivariate & Multivariate Analysis
- Shipment mode vs delivery delay
- Vendor vs delay
- Country vs delay
- Weight vs freight cost
- Insurance vs delay

#### Correlation Analysis
- Identified key cost and delay drivers

---

## 📈 Key Insights

### 🚚 Shipment Insights
- Air is the most used shipment mode.
- Air Charter is the most expensive shipping method.

### ⏱️ Delivery Insights
- Majority shipments are on time.
- Delays are driven by vendors and destination countries.

### 💰 Cost Insights
- Higher freight cost does NOT guarantee faster delivery.
- Significant cost optimization opportunity exists.

### 🌍 High Delay Countries
- Congo (DRC)
- Togo
- Benin
- Senegal
- Kenya

### 🏭 Vendor Insights
Poor vendor performance causes 4–5x more delays.

---

## 💡 Business Recommendations

- Implement vendor performance scorecards
- Build country risk-based shipment planning
- Reduce emergency Air Charter shipments
- Optimize freight cost strategy
- Build ML model for delay prediction

---

## 📊 Expected Business Impact

| Area | Improvement |
|------|-------------|
| Delivery Delay Reduction | 40–60% |
| Freight Cost Reduction | 15–25% |
| Vendor Efficiency | Improved |
| Shipment Planning | Data-Driven |

---

## 📌 Conclusion
This project demonstrates how data analytics can improve logistics performance, reduce costs, and increase delivery reliability.

---

## 👨‍💻 Author
**Ajaya Kumar Pradhan**

GitHub: https://github.com/Ajaya210

⭐ If you like this project, please give it a star!
