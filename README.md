# Walmart Sales Performance Dashboard (2010–2012)

Interactive Power BI dashboard analyzing Walmart weekly sales performance using economic indicators, seasonal patterns, and store-level comparisons.

This project demonstrates end-to-end data analysis, from raw dataset exploration to business insight generation using data visualization.

---

## 📊 Project Objective

The objective of this project is to analyze Walmart sales performance across multiple stores and identify the key factors influencing revenue trends.

The analysis focuses on:

- Sales trends over time
- Store performance comparison
- Economic indicators impact
- Seasonal and holiday effects
- Environmental factors such as temperature
- External economic conditions affecting consumer behavior

The final output is an interactive Power BI dashboard that supports data-driven decision making.

---

## 🖼️ Dashboard Preview

![Dashboard Preview](images/dashboard_preview.png)

---

## 📁 Dataset Information

The dataset contains **6,435 rows** and **8 columns**, representing weekly sales data across 45 Walmart stores from 2010 to 2012.

### Variables Included

| Column | Description |
|--------|-------------|
Store | Store identification number |
Date | Weekly sales date |
Weekly_Sales | Total weekly revenue |
Holiday_Flag | Indicates whether the week includes a holiday (1 = Holiday, 0 = Non-Holiday) |
Temperature | Regional temperature during the week |
Fuel_Price | Regional fuel price |
CPI | Consumer Price Index (inflation indicator) |
Unemployment | Regional unemployment rate |

---

## 📊 Data Exploration Focus

The dataset enables analysis of several important business questions:

- Do holidays significantly increase sales?
- Does unemployment affect purchasing behavior?
- How does inflation influence retail performance?
- Are weather conditions related to sales fluctuations?
- Which stores perform best?
- Are there seasonal patterns in revenue?
- What external factors influence consumer demand?

---

## 📈 Dashboard Components & Analysis

### 1️⃣ Sales Trend Over Time
**Visual:** Line Chart — Weekly Sales by Date  

**Purpose:**  
To analyze overall revenue movement and detect seasonal patterns across the period.

**Insight:**  
Sales remain relatively stable between 40M–50M with noticeable spikes during certain periods, likely driven by seasonal events and holidays.

**Business Value:**  
Helps identify peak demand periods for inventory planning and promotional strategies.

---

### 2️⃣ Average Weekly Sales KPI
**Visual:** Gauge  

**Purpose:**  
Provides a quick performance benchmark for average weekly revenue.

**Value:**  
Approximately **1.05 million** weekly sales.

**Business Value:**  
Useful for monitoring performance and setting sales targets.

---

### 3️⃣ Store Count KPI
**Visual:** Card  

**Purpose:**  
Displays the number of stores included in the analysis.

**Value:**  
45 stores.

---

### 4️⃣ Holiday vs Non-Holiday Sales
**Visual:** Pie Chart  

**Purpose:**  
Evaluates whether holiday periods influence revenue.

**Insight:**  
Holiday weeks show slightly higher sales compared to non-holiday periods.

**Conclusion:**  
Seasonal promotions and holiday demand contribute positively to sales.

**Business Value:**  
Supports strategic planning for marketing campaigns and inventory allocation.

---

### 5️⃣ Sales vs Temperature Relationship
**Visual:** Dual Line Chart (Sales & Temperature by Date)  

**Purpose:**  
Analyzes potential relationships between weather conditions and sales.

**Insight:**  
Temperature follows clear seasonal cycles, but sales spikes do not strongly correlate with temperature changes.

**Conclusion:**  
Weather conditions are not a primary driver of sales fluctuations.

**Business Value:**  
Indicates that operational planning should focus more on economic and seasonal factors rather than climate variations.

---

### 6️⃣ CPI Impact on Sales
**Visual:** Column Chart (CPI Categories: Low, Medium, High)

**Purpose:**  
Examines inflation influence on consumer purchasing behavior.

**Insight:**  
Sales decrease slightly during higher CPI periods, indicating moderate sensitivity to inflation.

**Conclusion:**  
Inflation has a measurable but not dominant effect on sales.

**Business Value:**  
Supports pricing strategies and demand forecasting during inflationary periods.

---

### 7️⃣ Unemployment Impact on Sales
**Visual:** Column Chart (Unemployment Categories)

**Purpose:**  
Evaluates economic stability impact on retail performance.

**Insight:**  
Higher unemployment levels are associated with lower average weekly sales.

**Conclusion:**  
Economic conditions significantly influence consumer spending behavior.

This is one of the strongest relationships identified in the analysis.

**Business Value:**  
Important for forecasting demand during economic downturns.

---

### 8️⃣ Fuel Price Impact on Sales
**Visual:** Bar Chart (Fuel Categories)

**Purpose:**  
Analyzes whether transportation costs affect customer purchasing behavior.

**Insight:**  
Fuel price variations show minimal impact on sales performance.

**Conclusion:**  
Fuel costs do not significantly influence retail demand.

**Business Value:**  
Indicates pricing strategy does not need strong adjustments based on fuel price changes.

---

### 9️⃣ Store Performance Comparison
**Visual:** Line Chart (Sales by Store)

**Purpose:**  
Compares revenue distribution across stores.

**Insight:**  
Significant variation exists between stores, suggesting location-based performance differences.

**Business Value:**  
Supports performance benchmarking and operational optimization.

---

### 🔟 Top Performing Stores
**Visual:** Horizontal Bar Chart

**Purpose:**  
Identifies stores with the highest revenue performance.

**Insight:**  
Certain stores consistently outperform others throughout the period.

**Business Value:**  
Helps identify best practices and opportunities for replication across locations.

---


## 🔍 Key Insights Summary

- Sales peaks occur during holiday periods, indicating strong seasonal influence.
- Higher unemployment levels correlate with lower retail sales performance.
- Inflation shows moderate influence on consumer spending.
- Fuel price changes have minimal impact on sales.
- Temperature follows seasonal patterns but does not strongly affect revenue.
- Store performance varies significantly across locations.
- Some stores consistently outperform others.

---

## 💼 Business Value

This dashboard can support:

- Strategic business planning
- Demand forecasting
- Promotional campaign timing
- Economic risk monitoring
- Store performance benchmarking
- Revenue optimization strategies
- Inventory planning during peak seasons

---

## 🚀 Recommended Next Steps

Based on the analysis, organizations could:

- Increasing marketing investment during peak seasonal periods
- Monitoring unemployment trends for demand forecasting
- Investigating strategies used by top-performing stores
- Optimizing inventory distribution across locations
- Developing targeted promotions during economic downturns
- Implementing store-level performance improvement programs

---

## 🛠️ Tools & Technologies

- Power BI
- Data Visualization
- Data Analysis
- Microsoft Excel / CSV

---

## 👤 Author

**Sarah Natalia Geraldine**  
E-mail: **geraldinesarahnatalia@gmail.com**
