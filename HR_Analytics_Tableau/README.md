# 👩‍💼 HR Analytics Dashboard (Tableau)

This **HR Analytics Dashboard** was designed in **Tableau** to provide a comprehensive view of workforce demographics, compensation, qualifications, leave balance, and employee growth trends. It is built on a simulated dataset but structured to replicate **real-world HR decision-making scenarios**.

---

## 🎯 Objective
To empower HR leadership with a **360° workforce intelligence platform** that enables them to:
- Monitor diversity, age distribution, and workforce composition  
- Analyze compensation by role and education level  
- Track employee growth trends year-over-year  
- Identify retention signals through leave balance analysis  

---

## 🗂️ Data Overview
- **Dataset Type**: Simulated HR dataset (~160 employees)  
- **Dimensions**: Job Title, Gender, Age, Education Qualification, Year of Joining  
- **Measures**: Salary, Leave Balance, Headcount Growth  

Data was cleaned and pre-aggregated for **Tableau extract performance optimization**, ensuring smooth interaction.

---

## 📊 Dashboard Components

### 1. **Employee Composition (Gender & Job Title)**
- **Who works with us?**: A donut tile visualizing total **headcount split by gender** (Female: 88, Male: 73).  
- **Job Title Distribution**: Horizontal bar chart showing employees across roles (Packaging Associate, Research Scientist, Product Manager, etc.).  
- **Technical Depth**: Used **COUNTD(Employee ID)** calculation to ensure unique staff counts, with **quick filters** enabling drilldowns by role and department.

---

### 2. **Demographics**
- **Age Distribution**: Histogram binned in 5-year intervals to analyze workforce spread (20–65).  
- **Gender Distribution Tile**: Percentage split (51.76% Male, 48.24% Female).  
- **Technical Depth**: Implemented **calculated bins** for age groups, dynamically parameterized for flexible bin sizing.

---

### 3. **Compensation Analysis**
- **Top Earners by Job**: Bar chart of highest salaries per role (e.g., Product Manager ~ $82.8K).  
- **Qualification vs Salary**: Box-and-whisker visualization correlating education level with average salary.  
- **Technical Depth**: Used **LOD (Level of Detail) expressions** to calculate average salary by qualification while maintaining individual employee granularity.

---

### 4. **Staff Growth Over Time**
- **Year of Join Analysis**: Running sum line chart showing cumulative staff growth from 2017–2023.  
- **Insight**: Hiring spike in 2020, dip in 2022.  
- **Technical Depth**: Applied **Tableau WINDOW_SUM()** function for cumulative headcount, with parameterized filters for year selection.

---

### 5. **Leave Balance Insights**
- **Avg Leave Balance by Role**: Dual chart showing both **average leave balance** and **number of staff with >20 days balance**.  
- **Insight**: Roles like *Research Scientist* and *Product Manager* carry consistently higher leave balances (~19–20 days), signaling potential **underutilized PTO**.  
- **Technical Depth**: Implemented conditional **IF statements** to flag employees above threshold, with visual encoding using diverging color scale.

---

### 6. **Salary Distribution**
- **Which Job Pays More?**: Horizontal bar chart ranking salaries across roles.  
- **Technical Depth**: Used **calculated fields for ranking** by salary and role aggregation. Added interactivity with **top-N filter parameter**.

---

## ⚙️ Technical Highlights
- Tableau features used: **Bins, LOD expressions, WINDOW_SUM, IF conditions, Parameters, Global Filters**.  
- Optimized for performance with **extracts** and **hidden unused fields**.  
- Dashboard size: 1200×800 (optimized for laptop + projector display).  
- Custom tooltips: Context-rich with employee counts and % contribution.  

---

## 📈 Business Impact (Simulated Scenario)
If implemented in a real HR environment, this dashboard would enable:  
- **20% faster workforce planning** through quick drilldowns by role & demographics.  
- **Identification of pay equity gaps** across gender & qualifications.  
- **Proactive retention strategy**, spotting roles with unused PTO as burnout/attrition signals.  
- **Executive-ready presentations**, reducing HR reporting time by 30%.  

---

## 📬 Author
**Sri Gayathri Sahithi Morapakala**  

