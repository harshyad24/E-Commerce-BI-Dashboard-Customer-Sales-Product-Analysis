# E-Commerce-BI-Dashboard-Customer-Sales-Product-Analysis
https://github.com/user-attachments/assets/45d94621-41d0-46f2-abb3-226398667c18

## 📌 Project Overview

This project analyzes **E-Commerce sales and customer behavior data** using **Power BI** to uncover insights on:

* Revenue performance
* Customer retention & churn
* Product performance
* Marketing & discount effectiveness

The goal was to design an **interactive Power BI dashboard** that supports business stakeholders in monitoring KPIs and making informed decisions.


---

## 📊 Dataset Details

The dataset includes:

* **Customer Data**: Customer ID, Gender, Subscription Status, Frequency of Purchases, Previous Purchases
* **Order Data**: Purchase Amount (USD), Payment Method, Shipping Type, Discount Applied, Promo Code Used
* **Product Data**: Item Purchased, Category, Size, Color, Season
* **Engagement Data**: Review Rating

---

## 🧹 Data Cleaning & Transformation (Power Query)

All data preparation was done inside **Power Query** in Power BI:

* Removed duplicates and invalid records.
* Replaced **null/blank values** with default values (e.g., 0 for returns).
* Standardized categorical fields (e.g., Payment Method, Shipping Type).
* Created **custom columns & measures** such as:

  * **Return Flag** (1 = Returned, 0 = Not Returned)
  * **Continent Mapping** (grouping countries for revenue analysis)
  * **Discount Effectiveness** (Revenue with vs without discount)

---

## 📊 Key KPIs

### 1. Sales Performance

* **Total Revenue**
* **Average Order Value (AOV)**
* **Sales by Category / Season / Location**
* **Discount Utilization Rate**

### 2. Customer Insights

* **Active vs Churned Customers**
* **Retention Rate**
* **Subscription vs Non-Subscription Revenue**
* **Purchase Frequency Analysis**

### 3. Product & Marketing Analysis

* **Top-Selling Products & Categories**
* **Return Rate % by Category**
* **Promo Code Impact**
* **Shipping Type vs Customer Satisfaction (Review Ratings)**

---

## 📊 Dashboard Features

The **Power BI dashboard** includes:

1. **Revenue & Trends**

   * Revenue by month, quarter, and season
   * YoY comparison (if data available)

2. **Customer Behavior**

   * Subscription vs Non-subscription analysis
   * Purchase frequency & repeat customers

3. **Product Insights**

   * Top & bottom performing categories
   * Return vs Sold item analysis

4. **Geographical Analysis**

   * Revenue by Country grouped into Continents
   * Regional breakdown of orders

5. **Marketing Impact**

   * Discount & Promo Code usage impact on revenue
   * Effect of Shipping Type on returns and satisfaction

---

## 📈 Insights & Recommendations

* **Subscription customers** generated higher repeat purchases → expand subscription offerings.
* **Seasonal spikes** (Winter months) drove higher revenue → increase inventory and marketing before peak season.
* **Free shipping** increased order volume, but express shipping correlated with more returns → improve delivery quality.
* **Clothing & Footwear** categories showed strong sales, but **Accessories** had a higher return rate → review product quality.
* Discounts and promo codes boosted sales but lowered margin → recommend **targeted discounts**.

---

## 📂 Project Structure

```
├── dashboard/                  # Power BI file (.pbix)
├── E-Commerce Analytic.mp4     # Dashboard demo video
└── README.md                   # Project documentation
```

---

## 🚀 How to Use

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/Ecommerce-Analytics.git
   ```
2. Open the `.pbix` file in **Power BI Desktop**.
3. Use slicers and filters to explore KPIs.
4. Watch the demo video for a walkthrough.

---

## 📧 Contact

👤 **Harsh Yadav**

* 📍 Data Analyst | Product Analyst
* 🔗 [LinkedIn](https://www.linkedin.com/in/harshyadav577/)
* 📧 [harshryadav24@gmail.com](mailto:harshryadav24@gmail.com)

---

✨ This project demonstrates **end-to-end analytics in Power BI**, from **data cleaning with Power Query** to **insightful dashboards**, providing businesses with actionable intelligence.


👉 Do you want me to also design a **dashboard preview image** (like a clean PNG thumbnail) so it looks professional at the top of your GitHub README?
