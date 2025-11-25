# 📊 Sales Case Study — Excel Analytics Project

This project analyzes daily product sales data to understand pricing behavior, demand patterns, profitability, and promotional performance.  
The goal is to support data-driven pricing and revenue decisions using Excel-based analytics.

---

## 📦 Dataset Overview
- **Format:** CSV → cleaned & enhanced in Excel
- **Time Period:** 1+ year of daily observations
- **Key Columns:**
  - Date  
  - Sales  
  - Cost of Sales  
  - Quantity Sold  
  - Unit Price  
  - Gross Profit & Gross Profit %  
  - Promo Days (Yes/No)  
  - Loss/Profit Indicator  
  - Daily Avg Cost per Unit

---

## 🛠️ Tools Used
- **Excel 365** — data cleaning, formulas, pivot tables, charts
- **PowerPoint/Canva** — presentation of insights
- **GitHub** — project documentation & portfolio hosting

✅ No Python, SQL, or BI tools required — fully Excel-driven.

---

## 🧮 Calculated Fields
Created directly in Excel:
- `Unit Price = Sales / Quantity Sold`
- `Gross Profit = Sales – Cost of Sales`
- `Gross Profit % = Gross Profit / Sales`
- `GP per Unit = Gross Profit / Quantity Sold`
- `Daily Avg Cost per Unit = Cost of Sales / Quantity Sold`
- `Promo Flag = Lowest 10% Unit Prices`
- `Loss/Profit Indicator = IF(GP > 0, "Profit", "Loss")`

---

## 📊 Visualizations Included
Located in `/presentation` folder:
- Daily Sales Trend (Line Chart)
- Promotion vs Normal Avg Quantity Sold (Bar Chart)
- Unit Price vs Quantity Sold (Scatter Plot)
- Profit vs Loss Days (Bar Chart)

These visuals form the basis of the project insights.

---

## 🔍 Key Insights
✅ Sales fluctuate daily — demand is inconsistent  
✅ Promotions significantly increase quantity sold  
✅ Strong negative price elasticity — customers react to price changes  
✅ Most days operate at a loss — pricing or cost structure needs review  
✅ Product moves well, but profitability is weak

---

## 💡 Business Recommendations
1. Review pricing strategy to avoid loss-making days  
2. Use promotions strategically — not continuously  
3. Negotiate supplier or production costs  
4. Track customer response to price changes over time  
5. Forecast demand to optimize stock & sales planning

---

## 📂 Repository Structure
