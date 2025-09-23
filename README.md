
# Understanding Consumer Complaints for Bank of America (2022–2025)

## Project Overview
This project analyzes consumer complaints for Bank of America between 2021 and 2024. The goal is to understand trends in complaint volumes, identify which products and services generate the most issues, and highlight areas requiring improvement.

The analysis covers:
- Trends in complaint volumes over time  
- Product and service-specific complaints  
- Geographic distribution of complaints across U.S. states  
- Sub-issue deep dives into key products  

---



## Data Preparation
- Removed irrelevant columns such as `Consumer disputed?`, `Tags`, and `Consumer complaint narrative`  
- Converted date columns into datetime format  
- Filled or removed missing values depending on context  
- Standardized the `State` column (removed territories, merged Washington D.C. into Virginia)  
- Created `Month` and `Year` features for trend analysis  

---

## Analysis and Insights

### 1. Complaint Trends
- Complaints remained stable overall, averaging 1,000–1,200 per month  
- Peaks occurred in March (tax season) and July (mid-year financial activities and travel)  

### 2. Product Analysis
- **Checking or Savings Accounts**: Most complaints, but fraud-related complaints declined in 2024. Debit and ATM card issues increased.  
- **Credit Cards**: Complaints rose sharply, more than 200% higher in 2024 than 2023. Driven by unresolved disputes, payment issues, unauthorized charges, and fraudulent account openings.  
- **Credit Reporting**: Fastest-growing product area, with large increases in identity misuse and reporting errors.  

### 3. Geographic Distribution
- California, Florida, and Georgia had the highest complaint volumes.  
- In all three states, “reporting company used your report improperly” grew sharply in 2024.  
- “Deposits and withdrawals” declined in 2024, suggesting improvements in operations.  

---

## Key Findings
- Fraud complaints declined in some areas, but disputes and reporting misuse are rising sharply.  
- Seasonal peaks in March and July highlight periods where additional customer support is needed.  
- Credit reporting misuse is the fastest-growing risk and requires stronger oversight.  

---
## Dataset
- Source: [Consumer Complaint Bank Of America Dataset](https://www.consumerfinance.gov/data-research/consumer-complaints/search/?chartType=line&company=BANK%20OF%20AMERICA%2C%20NATIONAL%20ASSOCIATION&dateInterval=Month&date_received_max=2024-12-31&date_received_min=2021-01-01&lens=Product&searchField=all&subLens=sub_product&tab=Trends)

---

## Tools and Libraries
- Python: pandas, numpy  
- Visualization: matplotlib, seaborn  
- Notebook: Jupyter / Google Colab  
