# Customer-Service-Request-Analysis
Customer Service Request Analysis (NYC 311 Data)   Python project analyzing NYC 311 service requests with data wrangling, visualization, and statistical testing. Includes complaint type frequency analysis, response time evaluation, and insights into customer service efficiency.
# 📊 Customer Service Request Analysis (NYC 311 Data)

## 📌 Project Overview
This project analyzes New York City’s 311 service request dataset using Python.  
The goal is to uncover complaint patterns, visualize major complaint types across cities, and evaluate response times.  
It demonstrates skills in **data wrangling, exploratory analysis, visualization, and statistical testing**.

---

## 🎯 Objectives
- Prepare a clean dataset for training and prediction  
- Perform exploratory data analysis (EDA)  
- Visualize complaint types by city  
- Analyze request closing times and response efficiency  
- Perform statistical tests (Kruskal‑Wallis H test) to identify significant variables  

---

## 🛠 Prerequisites
- Python basics  
- Pandas DataFrames  
- Libraries: Matplotlib, Seaborn  
- Knowledge of statistical analysis  

---

## 📂 Dataset Variables
Key columns include:  
- **Unique Key** – Complaint ID  
- **Created Date / Closed Date** – Timeline of request  
- **Agency / Agency Name** – Handling department  
- **Complaint Type / Descriptor** – Nature of complaint  
- **City / Borough** – Location of incident  
- **Status / Resolution Description** – Case outcome  
- **Coordinates (Latitude/Longitude)** – Geospatial mapping  

---

## 🔎 Tasks Performed
1. **Data Understanding**  
   - Import dataset, check shape, columns, null values  

2. **Exploratory Analysis**  
   - Frequency plots for missing values  
   - Missing value treatment (Closed Date, Complaint Type, City)  
   - Time elapsed calculation between Created and Closed Date  

3. **Complaint Analysis**  
   - Frequency plots by city  
   - Scatter/hexbin plots for Brooklyn complaints  
   - Top 10 complaint types  

4. **Visualization**  
   - Bar charts of complaint types  
   - Multi‑city comparison with grouped charts  
   - Average Request Closing Time visualization  

5. **Statistical Analysis**  
   - Kruskal‑Wallis H test to check distribution differences  

---

## 📈 Project Outcome
- Clean dataset prepared for prediction  
- Complaint types visualized across NYC cities  
- Insights into top complaint categories and response times  
- Statistical validation of significant variables  

---

## 🚀 How to Run
1. Clone this repository  
2. Install required libraries:  
   ```bash
   pip install pandas matplotlib seaborn
