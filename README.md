# Interactive Sales Performance & Target Analysis Dashboard
An interactive, data-driven sales performance dashboard designed to track, analyze, and visualize sales executive performance across 8 major Indian regions over a 5-day cycle. Built with advanced Excel capabilities including Pivot Tables, Pivot Charts, Slicers, and dynamic Form Controls (checkbox-toggled dashboard sections) to deliver actionable business intelligence.

## Dataset Used
- <a href=https://github.com/shubham9546appu-netizen/excel-sales-target-analytics/blob/main/Raw%20Data.xlsm>Dataset</a>

## 🎯 Project Objective
To transform raw daily sales data into a cohesive, interactive analytics tool that enables sales managers to:
- Monitor individual sales executive performance and identify top/bottom performers.
- Analyze regional sales patterns and track target hit rates.
- Identify the gap between actual sales and set targets to formulate corrective action plans.
- Provide a user-friendly, dynamic visual interface that allows stakeholder-specific views (by region and dashboard component).
---
## 🛠️ Tech Stack & Features
* **Platform:** Microsoft Excel (Office 365)
* **Data Visualizations:** Dynamic Column Charts, Horizontal Bar Charts, Line Charts, and Pie Charts.
* **Interactivity:**
  * **Regional Slicers:** Single-click filtering to switch between Chennai, Delhi, Mumbai, Nagpur, Patna, Pune, Ranchi, and Surat.
  * **Dynamic Section Toggles:** Integrated Form Controls (Checkboxes) to show/hide specific dashboards (Total Sales, Performance Trends, Target Hit %, and Target Gaps) for clutter-free analysis.
* **Formulas & Functions:** `SUM`, `AVERAGE`, `VLOOKUP`/`XLOOKUP`, Percentage Calculations, and Conditional Formatting.
---
## 📈 Key Insights & Business Recommendations
Based on the statistical analysis of the 41 sales executives across 8 regions (total target of 20,500 units, total sales of 12,022 units):
### 1. Overall Performance Summary
* **Total Sales Achieved:** 12,022 units
* **Cumulative Target:** 20,500 units
* **Overall Target Hit Rate:** **58.64%** (indicating a significant **41.36%** overall gap to target).
### 2. Regional Analysis & Performance Rankings
* 🏆 **Top Performing Region:** **Pune** leading with a **64.37%** hit rate (1,931 units sold across 6 executives).
* 🥈 **Runner-Up Region:** **Ranchi** at **63.35%** hit rate (1,267 units sold, 4 executives).
* 🔻 **Lowest Performing Region:** **Surat** at **52.95%** hit rate (1,059 units sold, 4 executives).
* *Business Action:* Investigate the sales processes and local demand drivers in Pune and Ranchi to replicate their success models in lower-performing regions like Surat (52.95%), Patna (53.30%), and Nagpur (53.60%).
### 3. Top Performers (High Flyers)
The top 3 sales executives globally who came closest to hitting their 500-unit target:
1. **Monika Sharma (Pune):** 464 units sold | **92.80%** Target Hit Rate
2. **Sureendra Kumar (Chennai):** 449 units sold | **89.80%** Target Hit Rate
3. **Anita Kumari (Delhi):** 426 units sold | **85.20%** Target Hit Rate
* *Business Action:* Recognize these high flyers and leverage them to mentor underperforming peers.
### 4. Critical Underperformers (Target Gap Analysis)
The lowest-performing executives requiring immediate support or training:
1. **Pooja Agarwal (Pune):** 147 units sold | **29.40%** Target Hit Rate
2. **Sudhir Kumar (Surat):** 149 units sold | **29.80%** Target Hit Rate
3. **Sushma Khandelwal (Delhi):** 179 units sold | **35.80%** Target Hit Rate
* *Business Action:* Standardize a PIP (Performance Improvement Plan) and conduct target-gap coaching sessions specifically focused on these individuals.
### 5. Daily Sales Trends
* **Peak Performance Day:** **Day 2** generated the highest sales volume (**2,585 units**), closely followed by Day 3 (2,532 units) and Day 4 (2,524 units).
* **Low Volume Days:** Day 1 (2,168 units) and Day 5 (2,213 units) saw lower momentum.
* *Business Action:* Identify why sales dip on Day 1 and Day 5. Focus on mid-week pipeline acceleration strategies to maintain high volume throughout the 5-day cycle.
---

## 📊 Dashboard Preview
<img width="1166" height="565" alt="Screenshot 2025-08-17 151339" src="https://github.com/user-attachments/assets/ea5de87a-78f0-4266-843e-85c553d5628f" />

## 📁 Repository Structure

```text
directory/
│
├── data/
│   └── sales_raw_data.csv        # Cleaned raw sales data
│
├── screenshots/
│   └── dashboard_preview.png    # Screenshot of the dashboard for README
│
├── Dynamic_Sales_Dashboard.xlsx # The main interactive Excel workbook
│
└── README.md                    # Project documentation
```

## 📋 Raw Data Schema

The dashboard processes a table of **41 sales representatives** with the following fields:

| Column Name | Data Type | Description |
|------------|-----------|-------------|
| Emp Code | String (Text) | Unique Identifier for each Sales Representative |
| Sales Executive | String (Text) | Name of the Sales Representative |
| Region | String (Text) | Operational sales region (8 unique regions) |
| Day 1 - Day 5 | Integer (Numeric) | Daily unit sales volumes |
| Total Sales | Integer (Numeric) | Cumulative sales over the 5-day cycle |
| Target | Integer (Numeric) | Fixed sales target of 500 units |
| Target Hit % | Percentage (Float) | Percentage of target achieved (`Total Sales / Target`) |
| Away From Target % | Percentage (Float) | Remaining gap to target (`100% - Target Hit %`) |

## 🚀 How to Interact with the Dashboard

* **Download the Repository:** Clone or download the ZIP file of this repository.
* **Open in Excel:** Open `Dynamic_Sales_Dashboard.xlsx` using Microsoft Excel (2016 or newer recommended).
* **Filter by Region:** Click on any region button (Slicer) at the top of the dashboard to filter charts and tables for a specific region.
* **Customize the View:** Use the **Dashboard 1–4** checkboxes to show or hide different dashboard sections dynamically.
* **Analyze Performance:** Review sales trends, target achievement percentages, and gaps from targets using the interactive charts and tables.
* **Explore Insights:** Compare sales executives across different regions and identify top and low performers.

## 👨‍💼 Contact 

* **Author:** Shubham Kumar
* **LinkedIn:** [Connect on LinkedIn](https://www.linkedin.com/in/shubham-kumar-0b537a364)
* **Email:** [shubham9546appu@gmail.com](mailto:shubham9546appu@gmail.com)

