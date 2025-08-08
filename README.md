# Call Center Performance Dashboard

This project was developed as part of an **interview task for a major company**.  
The company provided a detailed **Business Requirements Document**, outlining the KPIs, data transformation rules, and reporting expectations.

Using only **Microsoft Excel**, I transformed four raw datasets (`Call Log`, `CSAT`, `Roaster`, `Calendar`) into a fully interactive performance dashboard, applying:
- **Power Query** for data cleaning and transformation
- **Power Pivot** for data modeling and DAX measures
- **Pivot Tables & Pivot Charts** for interactive reporting

---

## 🔧 Data Transformation & Modeling
- Cleaned and standardized 4 datasets: `Call Log`, `CSAT`, `Roaster`, `Calendar`.
- Fixed time formats and converted durations into both `hh:mm:ss` and `decimal minutes`.
- Built calculated columns:
  - `Call Duration = Talk + Hold + ACW`
  - `AHT`, `Answer Speed`, `Numeric CSAT Score`
- Created a data model in **Power Pivot** with relationships and hierarchies.

---

## 📈 KPI Metrics & Dashboard Design
- KPIs tracked:
  - **Offered Calls**
  - **Answer Rate (AR)**
  - **Service Level % (SL)**
  - **Customer Satisfaction % (CSAT)**
  - **Average Speed of Answer (ASA)**
  - **Average Handle Time (AHT)**
  - **Composite KPI Score**
- Interactive visuals:
  - Daily Call Volume
  - Top 10 Agents by Call Volume
  - Top 5 Agents by KPI Score
  - Answer Rate & Service Level trends
  - Rating Distribution
  - Team Leader Performance
- Slicers for Month, Week, and Team Leader.

---

## 📊 Insights
- **Volume Dynamics**
  - Total Calls: 246,523
  - Daily Peak: 18,707 calls (Jan 28) → SL: 70.4%, AR: 37.8%
  - Daily Low: 2,770 calls (Jan 15) → SL: 94.3%, AR: 94.3%
- **Service Level & Answer Rate**
  - Avg SL: 66.93% (Target: 80%)
  - Avg AR: 89.02%
- **Speed & Efficiency**
  - ASA: 0.42 min (Target: 25 sec)
  - AHT: 4.71 min (Target: 4 min 40 sec)
- **Agent & TL Performance**
  - Top 5 by Volume: cmills, smorris, cdouglas, amendez, mallen
  - Top 5 by KPI Score: tayala, xcollins, shogan, cmorgan, dbridges
- **Customer Satisfaction**
  - Responses: 1,148
  - CSAT: 81.45% (Target: 80%)

---

## 🎯 Recommendations
1. Handle High Volume Spikes → Overflow routing during Jan 28 spike.
2. Optimize Mid-Month Coverage → Adjust staffing for Jan 12–14 & 23–26.
3. Improve ASA → Implement fast-lane queue to reduce ASA below 20 sec.
4. Targeted Coaching → Peer-led training from top performers.

---

## 🛠 Tools & Skills
- Microsoft Excel
- Power Query
- Power Pivot
- DAX Measures
- KPI Design
- Dashboard Visualization

---

## 📂 Files
- `Business_Requirements.pdf` → Original interview task requirements provided by the company
- `Call Center Performance Dashboard.pdf` → Dashboard overview (PDF)
- `RA Hiring Assessment V3 (1).xlsx` → Final Excel dashboard
- `README.md` → Project documentation
