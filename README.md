# Forecasting Tech Job Demand in Canada
#### CSCI 4050U – Final Project  
**Group Members:** Akshayan Balathas, Ryan Warrener, Ayaan Yousaf    
**Date:** December 8, 2025

--- 

🌐 Video Demo: Coming soon...

## 📝 Overview
This project uses a Long Short-Term Memory (LSTM) neural network to predict demand for tech jobs in Canada in 2026. The model is trained on monthly job vacancy rate data from the <i>Statistics Canada</i> Job Vacancy and Wage Survey (JVWS). The data spans from 2015 to 2025, and our model learns job market patterns to make predictions.

---

## 📊 Dataset
Statistics Canada. [Table 14-10-0406-01  Job vacancies, payroll employees, and job vacancy rate by industry sector, monthly, adjusted for seasonality](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1410040601)

Data: 
- **Job Vacancy Rate** for NAICS 54
- Monthly data from May 2015 to late 2025
- Linear time-based interpolation used for missing values during COVID-19 pandemic.

CSV can be found [here](data/target.csv)

---

## ⚙️ Setup Instructions
- Ensure you have Python installed on your machine.
### 1. Install dependencies
```bash
pip install requirements.txt
```

### 2. Run the notebook
Open and run [tech_demand_prediction.ipynb](/tech_demand_prediction.ipynb)

- Includes a walkthrough of: 
  - Preprocessing data
  - Creating neural network
  - Training
  - Evaluating
  - Forecasting