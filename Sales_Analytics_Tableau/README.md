# 💼 Sales Performance Dashboard (Tableau)

This **Sales Performance Dashboard** was built in **Tableau** to help sales leaders track performance across countries, monitor top-performing sales representatives, and analyze shipment volumes. The dashboard is based on a simulated dataset but designed to replicate a **real-world sales performance management system**.

---

## 🎯 Objective
To enable sales management to:
- Track revenue contributions by **country** and **salesperson**
- Identify **top-performing reps** and underperforming regions
- Monitor **shipment volumes** and sales trends
- Provide executives with a **business summary view**

---

## 🗂️ Data Overview
- **Dataset Type**: Simulated global sales transactions  
- **Dimensions**: Country, Salesperson, Transaction Count  
- **Measures**: Revenue (Amount), Boxes Shipped  

---

## 📊 Dashboard Components

### 1. **Country-wise Sales Analysis**
- Bar chart showing total revenue by country (Australia, UK, India, USA, Canada, New Zealand).  
- Highlights top markets driving revenue.  
- **Technical Depth**: Implemented **relative contribution (%) calculations** to compare countries on a normalized scale.

---

### 2. **Salesperson Performance**
- Horizontal bar leaderboard of revenue by individual sales reps (e.g., Ches Bonnell, Oby Sorrel, Madelene Upcott).  
- **Technical Depth**: Used **RANK() table calculations** to dynamically highlight top 5 performers with conditional formatting.

---

### 3. **Business Summary KPIs**
- KPI tiles showing:  
  - **Total Transactions**: 1,094  
  - **Boxes Shipped**: 177,007  
  - **Total Sales**: $6.18M  
- **Technical Depth**: Applied **LOD calculations** to ensure KPIs remained accurate even with applied filters.

---

## ⚙️ Technical Highlights
- Tableau features used: **LOD, Table Calculations, KPIs, Global Filters**  
- Dashboard optimized with extracts for faster aggregation  
- Configured **Top N parameter** to dynamically focus on top-performing reps  

---

## 📈 Business Impact (Simulated Scenario)
If implemented in a real sales environment:  
- **15% improvement in resource allocation** by identifying high-performing reps  
- **Faster quarterly reviews**, reducing manual reporting by ~10 hours/month  
- Ability to **shift focus to underperforming regions**, boosting sales growth  

---

## 📬 Author
**Sri Gayathri Sahithi Morapakala** 
