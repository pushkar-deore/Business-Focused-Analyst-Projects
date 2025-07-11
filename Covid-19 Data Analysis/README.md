# 🦠 COVID-19 Data Analysis Project

## 📌 Project Overview
This project involves in-depth analysis of the global COVID-19 pandemic using real-world data sourced from Kaggle. It includes time-series analysis, country-wise trends, and insights into infection severity, recovery, and mortality.

---

## 📂 Dataset
**Source:** [Kaggle COVID-19 Dataset](https://www.kaggle.com/datasets/imdevskp/corona-virus-report)  
**File used:** `covid_19_clean_complete.csv`

---

## 🛠️ Tools & Technologies
- Python
- Pandas
- Seaborn
- Plotly
- Matplotlib

---

## 🎯 Objectives
- Analyze trends by **country**, **date**, and **severity**
- Perform **time series analysis**
- Use `groupby()` for **aggregation**
- Create compelling **visualizations**
- Calculate **recovery** and **death rates**

---

## 🔍 Key Steps
1. **Data Cleaning**
   - Renamed columns
   - Converted `Date` to datetime
   - Filled missing values in `Recovered`

2. **Aggregation**
   - Total cases per country
   - Global daily trend over time
   - Country-specific time series

3. **Visualizations**
   - Global trend line plot
   - Top 10 countries (bar chart)
   - India trend analysis
   - Interactive Plotly charts

4. **Feature Engineering**
   - Added `Active`, `DeathRate`, `RecoveryRate` columns

---

## 📊 Sample Insights
- **Top countries**: USA, India, Brazil led in total confirmed cases.
- **Global trend**: Case count grew sharply during early 2020, then flattened.
- **Recovery Rate**: India showed a strong upward trend post-peak.
- **Death Rate**: Countries like Italy and UK had higher early fatality percentages.

---

## 📁 Project Files
- `covid_analysis.ipynb` → Main notebook
- `covid_19_clean_complete.csv` → Raw dataset
- `covid_final_cleaned.csv` → Cleaned output
- `README.md` → Project documentation

---

## 📌 Conclusion
This project demonstrates how data science can be used to extract meaningful insights from a global crisis. It showcases time-series analysis, data wrangling, visualization, and interpretation skills essential for data analysts.

---

## 🔗 Author
**Pushkar Deore**  
_Data Analyst in training | Python | Pandas | Data Science Projects_

