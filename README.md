# ecomerce_dashaord
# 🛍️ Ecommerce Shop Dashboard

This is an interactive and visually appealing **Ecommerce Analytics Dashboard** created in **Power BI**, designed to track and visualize key ecommerce metrics like amount, quantity, profit, and average order value (AOV).

---

## 📊 Key Features

- ✅ KPIs: Total Amount, Quantity, Profit, and AOV
- 📆 Time-based filtering: Quarter-wise analysis
- 🌐 Regional filtering: State-wise analysis
- 📉 Visualizations:
  - Profit by **Subcategory**
  - Quantity by **Category**
  - Quantity by **Payment Mode**
  - Amount by **Customer Name**
  - Profit Trend by **Month**

---

## 🧹 Data Cleaning Performed

- Removed **null or blank values** from key columns
- Converted **data types** (e.g., date, numeric fields)
- Removed **duplicate rows**
- Standardized **category names**
- Handled **missing values** using conditional replacements
- Created a **date table** for proper time intelligence

---

## 🧠 DAX Measures Used

- **Total Profit**:
  ```DAX
  Total Profit = SUM(Sales[Profit])
