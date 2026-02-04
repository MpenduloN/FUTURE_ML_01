# Coffee Shop Sales Forecasting Dashboard

## Overview
This project is a **Power BI dashboard** built to analyze and forecast coffee shop sales.  
It provides insights into daily sales trends, revenue by coffee type, and payment methods, helping management make data-driven decisions.  
The project also includes Python forecasting code run on **Google Colab** and uses a **Kaggle dataset** as the source data.

---

## Features
- **Daily Sales Trend:** Line chart showing total sales over time.
- **Forecasting:** Predicted sales based on historical data using Python in Google Colab (exported to Power BI for visualization).
- **Interactive Slicers:** Filter by payment method (`Cash`, `Card`) and coffee type.
- **Total Sales KPI:** Quick summary of overall revenue.
- **Clean & Professional Design:** White background, blue charts, black title, optimized for readability.

---

## Dataset
- Source: [Kaggle](https://www.kaggle.com/)  
- File: `sales.csv`  
- Rows: 262  
- Columns:
  - `date` — Date of transaction  
  - `date_time` — Full timestamp  
  - `Cash_type` — Payment method  
  - `money` — Sale amount  
  - `coffee_name` — Coffee type  

> The CSV dataset is included in this repo for reference.

---

## Tools Used
- **Power BI Desktop** — for building dashboard and visualizations  
- **Python (Google Colab)** — for generating forecasted sales  
- **CSV** — lightweight and compatible with Power BI  
- **Kaggle** — source dataset  

---

## How to View
### Option 1 — GitHub
- View screenshots in this repo (included)  
- See dashboard structure and layout  

### Option 2 — Power BI Service (Recommended)
1. Open the PBIX file in Power BI Desktop  
2. Or publish it to Power BI Service to get a web link viewable on any device (phone, tablet, browser)
---

## Key Learnings
- Loading and preparing CSV data in Power BI  
- Creating interactive visuals (line chart, slicers, card KPI, pie charts)  
- Optimizing dashboards for low RAM devices  
- Integrating Python forecasts using Google Colab  
- Using Kaggle datasets for real-world analytics  
- Professional layout design for business dashboards

---

## Author
**Mpendulo Ngoma**  
[Email](mailto:ngomampendulo92@gmail.com) | [LinkedIn](Mpendulo Ngoma) 

---

## Notes
- Keep visuals simple to avoid freezes on low RAM machines  
- Save frequently when working with Power BI Desktop  
- Python code is included for generating forecast data in Google Colab
