# BDM-CAPSTONE-PROJECT-
# 🛒 Supply Chain Analytics – Pure O Naturals  

## 🌟 Project Overview  
This repository contains my **Business Data Management (BDM) capstone project** analyzing the supply chain of **Pure O Naturals**, a supermarket selling **fruits, vegetables, and dairy products**.  

The project dives into:  
✅ Cleaning messy stock & sales data  
✅ Calculating **KPIs (Sell-Through Rate, Stock-Out %, Wastage %)**  
✅ Visualizing trends in **Excel & Power BI**  
✅ Building a **SARIMA forecasting model** for demand prediction  
✅ Delivering a **business report & viva presentation**  

---

## 🎯 Objectives  

- 📂 Integrate **stock received & sales data**  
- 📈 Measure supply chain efficiency using custom KPIs  
- 🔎 Identify inefficiencies (delays, wastage, low utilization)  
- 🔮 Forecast demand to enable **data-driven procurement**  

---

## 🗂️ Dataset Description  

| File | Description | Duration |
|------|-------------|----------|
| `Stock_Received.xlsx` | SKU-wise batch stock received | Dec 2024 – Feb 2025 |
| `Sales_Data.xlsx` | Daily transactions (date, SKU, quantity sold) | Dec 2024 – Feb 2025 |

---

## 🛠️ Preprocessing Workflow  

1. 🔧 Cleaned raw data (handled missing values, standardized SKUs)  
2. 🧹 Converted columns to proper data types  
3. 🔗 Merged stock & sales into a single dataset  
4. 📊 Created derived metrics:  

   - **Sell-Through Rate (STR)** = `(Sales ÷ Stock) × 100`  
   - **Stock-Out %** = `(Days Out-of-Stock ÷ Total Days) × 100`  
   - **Wastage %** = `(Unsold Stock ÷ Total Stock) × 100`  

---

## 📊 Analysis & Insights  

- STR observed at **28.6%** → indicates low stock utilization  
- Identified **stock-out patterns** and seasonal demand fluctuations  
- Created **Excel pivot tables & Power BI dashboards** for visualization  

**Example Chart:**

![Sales vs Stock]

---

## 🔮 Forecasting  

- Model Used: **SARIMA (Seasonal ARIMA)**  
- Library: `statsmodels`  
- Evaluation:  
  - **AIC = 1156.74**  
  - **BIC = 1165.98**  
- Forecast: Daily sales for selected SKUs, enabling better procurement  

📈 *Future demand patterns were captured to avoid overstocking & understocking issues.*  

---

## 🛠️ Tech Stack  

| Category | Tools/Tech |
|----------|------------|
| Data Cleaning | Excel, Power Query, Pandas |
| Visualization | Excel Charts, Power BI, Matplotlib |
| Forecasting | Python, SARIMAX (statsmodels) |
| Reporting | MS Word, Viva Presentation |

---

## 🚀 Results  

- 📉 Found inefficiencies in supply chain (low STR, frequent delays)  
- 🔮 Predicted demand to guide **inventory optimization**  
- 🏆 Successfully defended in **BDM viva** and finalized report  

---

## 🔭 Future Work  

- 🧩 Apply **Clustering** for customer segmentation  
- 📊 Build **real-time inventory dashboards** in Power BI / Streamlit  
- ⏳ Extend dataset for long-term forecasting  

---

⭐ If you found this project interesting, **give it a star** on GitHub! ⭐  
