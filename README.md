# 📊 Smartphone Sales and Customer Insights Dashboard

This project presents a comprehensive **Tableau dashboard** analyzing smartphone sales data to uncover customer insights. The goal was to visualize key business metrics such as revenue, customer ratings, and brand performance using interactive charts and filters.

---

## 🔧 Tools & Technologies Used

- **Tableau** – For creating interactive dashboards and visualizations  
- **Microsoft Excel / CSV** – For data cleaning and preprocessing  
- **SQL** – Used for initial data querying and summarization  
- **Git & GitHub** – For version control and showcasing work

---

## 📁 Dataset

- **File**: `Sales_Enhanced.csv`  
- **Size**: ~1,500 rows  
- **Fields**:
  - Brand  
  - Mobile  
  - Storage & Memory  
  - Selling Price & Original Price  
  - Discount  
  - Customer Rating  
  - Market Share (%)  
  - Revenue (calculated)

The dataset was manually enhanced and cleaned to ensure consistency before importing into Tableau. Some initial filtering and revenue calculations were done using basic **SQL queries**.

---

## 📌 Dashboard Highlights

The dashboard consists of **6 interactive visualizations**:

1. **Total Revenue by SmartPhone Brands** – Horizontal bar chart
2. **Market Share by Brand** – Pie chart showing percentage split
3. **Average Rating by Brand** – Bar chart with color gradient by rating
4. **Top 10 Smartphones by Avg. Rating** – Horizontal bar chart
5. **Top 10 Smartphones by Total Revenue** – Horizontal bar chart
6. **Price vs Rating** – Scatter plot with trend line showing relationship

**Interactive Brand Filter** is added to dynamically update all charts.

---

## 📈 Key Insights

- 📱 **Apple** dominates the smartphone market in both revenue and customer rating.
- 💵 A **positive correlation** exists between smartphone price and customer rating.
- 📊 Budget brands like **vivo** and **realme** maintain strong ratings despite lower prices.
- 🔝 Models like *vivo S2* and *iPhone XS* stand out in top-rated devices.

---

## ▶️ How to Use

1. Clone or download this repository.
2. Open `Smartphone_Dashboard.twbx` in **Tableau Public** or **Tableau Desktop**.
3. Use the dropdown filter to explore brand-specific performance.
4. Interact with charts and hover for detailed tooltips.

---
