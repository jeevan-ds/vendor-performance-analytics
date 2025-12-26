<img width="1024" height="1536" alt="image" src="https://github.com/user-attachments/assets/7545db17-36b0-46c8-afb8-ad6697ba014e" />

Data-driven analysis of vendor sales, profitability, inventory efficiency, and strategic optimization using SQL and Python.
#  Vendor Performance Data Analysis

##  Project Overview
This project focuses on evaluating **vendor and brand performance** using sales, purchase, inventory, and profitability data. The objective is to identify high-performing vendors, uncover inefficiencies in inventory movement, analyze profit margins, and recommend actionable strategies to improve overall business profitability.

The analysis integrates **SQL, Python, and data visualization** to deliver data-driven insights that support vendor optimization and strategic decision-making.

---

##  Business Problem
Organizations often work with multiple vendors but lack clear visibility into:
- Which vendors drive the most revenue and profit
- Which vendors incur high logistics and inventory costs
- Which brands have high margins but low sales potential
- Where pricing, promotions, or renegotiations are needed

Without structured analysis, businesses risk **overstocking, low margins, and poor vendor ROI**.

---

##  Project Objectives
- Evaluate vendor-level sales, purchases, and profitability
- Measure inventory efficiency using **Stock Turnover**
- Identify high-margin but low-sales brands for promotion
- Analyze freight cost impact on profitability
- Classify vendors into strategic action categories

---

##  Data Sources
The analysis is based on structured transactional data including:
- **Purchases**
- **Sales**
- **Vendor Invoices**
- **Purchase Prices**
- **Freight Costs**

Data was stored and queried using an **SQLite database**.

---

##  Data Cleaning & Preparation
- Removed inconsistent and invalid records (zero/negative sales, margins, or quantities)
- Aggregated data at **Vendor** and **Brand** levels
- Engineered key metrics:
  - Total Sales Dollars
  - Total Purchase Dollars
  - Gross Profit
  - Profit Margin
  - Stock Turnover Ratio
- Ensured consistency across joined tables

---

##  Exploratory Data Analysis (EDA)

### Key Analyses Performed:
- Vendor-wise purchase vs sales comparison
- Brand-level profitability analysis
- Freight cost contribution by vendor
- Sales quantity vs purchase quantity trends
- Profit margin distribution across brands

### Strategic Segmentation:
Brands were segmented using percentile thresholds:
- **Low Sales**: Below 15th percentile ($560.30)
- **High Profit Margin**: Above 85th percentile (64.97%)

This helped identify **high-margin but underperforming brands**.

---

##  Key Insights

- A small group of vendors contributes the majority of purchase value
- Several brands have **high margins but low sales**, representing untapped profit potential
- Some vendors show strong sales but weak margins due to pricing or freight costs
- High freight costs significantly reduce net profitability for select vendors
- Inventory inefficiencies were identified through low stock turnover rates

---

##  Visualizations
The project includes:
- Scatter plots for Sales vs Profit Margin
- Vendor performance comparison charts
- Inventory efficiency plots
- Profitability segmentation visuals

These visualizations enable quick identification of:
- Promotion candidates
- Pricing optimization opportunities
- Vendors to retain, renegotiate, or phase out

---

##  Business Recommendations

###  Promote
- Brands with **high profit margin but low sales**

###  Renegotiate
- Vendors with high sales but low margins
- Vendors with disproportionately high freight costs

###  Optimize or Phase Out
- Low sales, low margin, slow-moving brands

###  Inventory Optimization
- Improve replenishment planning for fast-moving vendors
- Reduce overstocking for slow-moving inventory

---

##  Tools & Technologies
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **SQL (SQLite)**
- **Jupyter Notebook**
- **Data Visualization**
- **Statistical Analysis**

---

##  Outcome
This project delivers a **data-driven vendor evaluation framework** that helps businesses:
- Improve profitability
- Optimize inventory
- Strengthen vendor relationships
- Make informed pricing and promotional decisions

---

##  Future Enhancements
- Add predictive models for demand forecasting
- Automate vendor performance dashboards
- Integrate time-series inventory analysis
- Apply clustering for vendor segmentation

---
 



⭐ *If you found this project insightful, feel free to star the repository!*
