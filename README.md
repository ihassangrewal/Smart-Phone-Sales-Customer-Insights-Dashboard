# 📱 Smartphone Sales & Customer Insights Dashboard

This project showcases an **interactive Tableau dashboard** built to explore smartphone sales data, uncover customer insights, and identify patterns in brand performance, pricing, and customer satisfaction. It simulates a real-world scenario where business teams need to understand market dynamics quickly through visual storytelling.

---

## 🛠 Tools & Technologies Used

- **Tableau** – Interactive dashboard creation and visual analytics  
- **Excel / CSV** – Data preprocessing and enhancement  
- **SQL** – Used for basic filtering, grouping, and revenue aggregations  
- **Git & GitHub** – Project versioning and showcasing

---

## 📂 Dataset

- **Filename**: `Sales_Enhanced.csv`  
- **Size**: ~1,500 rows  
- **Data Fields**:
  - `Brand`  
  - `Mobile Model`  
  - `Memory`, `Storage`  
  - `Selling Price`, `Original Price`, `Discount`  
  - `Customer Rating`  
  - `Market Share (%)`  
  - `Revenue` (derived)

The dataset was manually cleaned and enhanced for consistency. SQL was used to compute total revenue per model and filter for top-performing devices by different criteria.

---

## 📊 Dashboard Overview

The **Smart Phone Sales & Customer Insights Dashboard** includes 6 key visualizations:

1. **Total Revenue by Smartphone Brands** – Highlights overall revenue leaders
2. **Market Share by Brand** – Pie chart representing brand market proportions
3. **Average Rating by Brand** – Color-graded bar chart based on customer feedback
4. **Top 10 Smartphones by Average Rating** – Shows highest-rated models
5. **Top 10 Smartphones by Total Revenue** – Reveals highest-earning models
6. **Price vs Rating** – Scatter plot with trend line analyzing price-value relationship

➡️ A **brand filter** allows dynamic updates across all visualizations.

---

## 🔍 Insights Uncovered

- 📈 **Apple** leads both in revenue and customer satisfaction, indicating brand trust and premium pricing power.
- 📉 **SAMSUNG** holds strong market share but trails slightly behind in average ratings.
- 🥇 **vivo S2** and **iPhone XS** are among the highest-rated devices.
- 💰 There's a **moderate positive correlation** between price and customer rating – suggesting premium smartphones tend to receive better feedback.
- 🏷️ Brands like **realme**, **POCO**, and **Infinix** offer competitive ratings at lower price points, appealing to budget-conscious customers.
- 🔟 **Top revenue models** are dominated by iPhones, especially Pro/Max variants, revealing Apple’s strength in upselling.

---

## 🧭 How to Use This Dashboard

1. Open `Smart Phone Sales & Customer Insights Dashboard.twbx` in **Tableau Desktop** or **Tableau Public**.
2. Use the **Brand filter dropdown** to explore specific brand-level performance.
3. Interact with charts by hovering for detailed tooltips or clicking elements to filter visuals contextually.

---

## 🔮 Future Work

- Incorporate **time series data** to analyze trends across quarters/years  
- Add **geographic segmentation** to see how sales vary by region  
- Include **product return rates** or **warranty claims** to balance revenue with reliability  
- Build a **Story mode** in Tableau to walk viewers through findings  
- Integrate with a **live SQL database** for real-time updates
