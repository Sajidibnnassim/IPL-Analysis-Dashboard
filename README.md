# 🏏 IPL Data Analytics Dashboard (2008 - 2025)

## 📌 Project Executive Summary
This project aims to transform 17 years of historical IPL data into an actionable, interactive **Power BI Dashboard**. The goal was to provide high-level insights for stakeholders while maintaining granular control for cricket analysts. By utilizing advanced data modeling and DAX, this dashboard offers a comprehensive view of team performance, player milestones, and tournament trends across every season since the inception of the IPL.


## 🎯 Core Business Objectives
The primary focus was to translate complex cricket statistics into a user-friendly interface. Key business requirements included:
* **Dynamic Season Navigation:** Enabling users to switch between any IPL season (2008–2025) and see the entire dashboard update instantly.
* **Contextual Data Rendering:** Automatically switching images and stats based on the selected season, including team logos for the Winner and Runner-Up.
* **KPI Visualization:** Tracking both primary KPIs (Tournament Winners) and secondary KPIs (Total 4s, 6s, Centuries, and Venue statistics).

## 🛠 Technical Implementation & Methodology
### Data Engineering & Modeling
* **Data Sources:** Cleaned and transformed historical IPL datasets.
* **Modeling:** Designed a Star Schema (or Snowflake schema) to optimize performance for slicer-based filtering across multiple tables.

### Key DAX Measures
Custom DAX was implemented to handle unique IPL scoring rules and dynamic logic:
* **Points System:** `Total Points = (Wins * 2) + (Ties * 1) + (No Results * 1)`
* **Dynamic Visualization:** Utilized field parameters/measures to toggle player images and team badges based on season filters.
* **Aggregation:** Optimized measures for calculating cumulative metrics (Total Sixes, Fours, and Centuries) across selected timeframes.

## 📈 Key Insights & Features
* **Orange & Purple Cap Analysis:** Real-time visibility into the season's top run-getters and wicket-takers.
* **Points Table Analysis:** An interactive table displaying Win-Loss records, NR (No Results), and Ties, allowing for performance trend analysis.
* **Responsive Design:** A clean, professional UI/UX layout optimized for stakeholders to quickly identify top-performing teams.

# 🏏 IPL Analysis Dashboard (2008 - 2025)

## 🏆 Dashboard Preview
![IPL Dashboard](https://raw.githubusercontent.com/Sajidibnnassim/IPL-Analysis-Dashboard/main/IPL_Dashboard.png)

---

### 👤 Author
**Sajid Shaikh** 

---

---
*If you find this project useful or have any feedback on the data modeling approach, please feel free to open an issue or reach out directly!*
