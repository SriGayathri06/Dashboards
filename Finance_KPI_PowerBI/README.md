# 💰 Finance KPI Dashboard (Power BI)

This **Finance KPI Dashboard** was designed in **Power BI** to provide C-suite executives with real-time visibility into financial performance. It highlights revenue, profit margins, expenses, and year-over-year growth with dynamic drilldowns. The dashboard is based on a simulated dataset but structured to mimic **real-world executive reporting needs**.

---

## 🎯 Objective
To equip finance executives with a **KPI-driven dashboard** that enables:
- Tracking of **revenue, expenses, and profitability**
- Monitoring **YOY growth trends**
- Identifying **cost centers** and performance bottlenecks
- Supporting faster and more accurate decision-making

---

## 🗂️ Data Overview
- **Dataset Type**: Simulated financial statements  
- **Dimensions**: Department, Time (Month/Quarter/Year)  
- **Measures**: Revenue, Expenses, Profit, Margins, YOY Growth  

---

## 📊 Dashboard Components

### 1. **Executive KPI Tiles**
- Revenue, Expenses, Net Profit, and Profit Margin % shown as large KPI cards  
- **Technical Depth**: Implemented **DAX measures** for YOY% and margin calculations (e.g., `Profit Margin = DIVIDE(Profit, Revenue)`).

---

### 2. **Trend Analysis**
- Line chart tracking revenue and profit trends across time (monthly/quarterly).  
- **Technical Depth**: Used **time intelligence functions** (`DATEADD`, `SAMEPERIODLASTYEAR`) for YOY comparisons.

---

### 3. **Expense Breakdown**
- Donut/treemap chart showing expense distribution by department (HR, Operations, Marketing, R&D).  
- **Technical Depth**: Leveraged **hierarchical drilldowns** for expense categories → subcategories.

---

### 4. **Departmental Performance**
- Comparative bar charts showing revenue vs. expense by department.  
- **Technical Depth**: Created **custom DAX ratios** for cost-to-revenue efficiency.

---

## ⚙️ Technical Highlights
- Power BI features used: **DAX Measures, Time Intelligence, Drilldowns, Slicers**  
- Implemented **calculated tables** for YOY growth tracking  
- Model optimized with **star schema** for clean relationships  

---

## 📈 Business Impact (Simulated Scenario)
If implemented in a real finance environment:  
- **40% faster month-end reporting** due to automated YOY/KPI calculations  
- **Reduced executive decision-making lag** by centralizing KPIs in one view  
- **Enhanced budget allocation decisions**, saving potential overspend of 8–10% annually  

---

## 📬 Author
**Sri Gayathri Sahithi Morapakala**  
