# Olist Brazilian E-Commerce Data Analytics

## 📊 Data Analytics Hackathon — Gradient

This project was developed as part of the **Data Analytics Hackathon conducted by Gradient**.

We analysed the **Olist Brazilian E-Commerce dataset**, containing approximately **100,000 orders** from **September 2016 to October 2018**, to understand marketplace performance, customer satisfaction, delivery performance, and areas for operational improvement.

---

## 🎯 Problem Statement

The objective of this project is to provide a consolidated understanding of Olist's marketplace performance and identify the factors associated with customer satisfaction and dissatisfaction.

Our analysis focuses on six core business questions:

1. **Marketplace Performance Over Time**
2. **Delivery Performance & Customer Satisfaction**
3. **Seller & Geographic Patterns**
4. **Product Category Performance**
5. **Payment Behavior**
6. **Root Cause Analysis**

---

## 🔍 Analytical Approach

We performed:

- Data understanding and cleaning
- Data preparation and merging
- Exploratory Data Analysis (EDA)
- Monthly performance analysis
- Delivery delay analysis
- Customer review analysis
- Geographic analysis
- Product category analysis
- Payment method analysis
- Correlation analysis
- Business-focused recommendations

---

## 💡 Key Findings

### 🚚 Delivery & Customer Satisfaction

Delivery performance showed the clearest relationship with customer satisfaction.

| Delivery Timing | Average Review Score |
|---|---:|
| More than 14 days early | **4.31** |
| 8–14 days early | **4.30** |
| 1–7 days early | **4.19** |
| On time | **3.16** |
| 1–7 days late | **1.74** |
| More than 7 days late | **1.71** |

The correlation between **delivery delay and review score was -0.269**, indicating that higher delivery delays are associated with lower customer review scores.

> **Key Insight:** Late deliveries are strongly associated with lower customer satisfaction.

---

### 🛍️ Product Categories

The top categories by revenue included:

- Health & Beauty — approximately **R$1.26M**
- Watches & Gifts — approximately **R$1.21M**
- Bed Bath Table — approximately **R$1.04M**
- Sports & Leisure — approximately **R$0.99M**
- Computers & Accessories — approximately **R$0.91M**

An important observation is that **order volume and revenue do not always tell the same story**.

---

### 💳 Payment Behavior

Credit card was the dominant payment method with approximately **76,500 orders**, followed by boleto with approximately **19,800 orders**.

---

### 📍 Geographic Performance

We compared customer states using:

- Order volume
- Average review score
- Late-order count
- Late-order percentage

This helped identify geographical areas that may require greater operational attention.

---

## 🎯 Recommendations

Based on our analysis, we recommend:

1. **Improve delivery reliability** and reduce late deliveries.
2. **Prioritize higher-risk geographical areas** based on delivery and satisfaction metrics.
3. **Monitor delivery performance across high-volume categories.**
4. **Proactively communicate delivery delays** to customers.

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- GitHub

---

## 📁 Project Structure

```text
olist-data-analytics-hackathon/
│
├── README.md
│
├── notebook/
│   └── Olist_Data_Analysis.ipynb
│
└── presentation/
    └── Olist_Marketplace_Analysis.pptx
