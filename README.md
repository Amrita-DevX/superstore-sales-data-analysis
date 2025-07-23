# 📊 Superstore Sales Data Analysis

Welcome to the **Superstore Sales Data Analysis** project!  
This repository contains a detailed **Exploratory Data Analysis (EDA)** using Python ,**time series analysis to get the sales for forecasting for next 7 days** and a **Power BI Dashboard** built on the Superstore Sales dataset.

---

## 📂 Project Structure
```
├── data/ 
          ├── superstore_sales.csv 
├── notebooks/ 
          ├── Superstore Sales EDA.ipynb 
          ├── Superstore Sale Time Series Analysis.ipynb 
├── powerbi/ 
          ├── Superstore Sale BI.pbix` 
          ├── Superstore Sale Dashboard.png 
          ├── Superstore Sale Dashboard video.mp4
└── README.md
```
---

## 📁 Files Included

| File | Description |
|-----|-------------|
| `data/Superstore_Sales_Dataset.csv` | Dataset used for analysis |
| `data/Superstore_Sales_Result.csv` | Dataset After cleaning used for visualization |
| `notebooks/Superstore Sales EDA.ipynb` | Python Notebook for EDA |
| `notebooks/Superstore Sale Time Series Analysis.ipynb` | Python Notebook for time series analysis to get the sales for forecasting for next 7 days |
| `powerbi/Superstore Sale BI.pbix` | Power BI Dashboard file |
| `powerbi/Superstore Sale Dashboard.png` | Dashboard screenshot |
| `powerbi/Superstore Sale Dashboard video.mp4` | Dashboard video walkthrough |

---

## 📌 Dataset Description
The dataset contains retail sales transactions including:
- Order IDs, Dates
- Product Categories & Sub-categories
- Customer Details
- Sales
- Geographic data (City, State, Region)
- Shipping Mode

---

## 📈 Exploratory Data Analysis (EDA)

### 🔧 **Libraries Used**
- pandas
- numpy
- matplotlib
- seaborn
- plotly

### 📝 **Insights Generated**
- **Most Valuable Customers** based on revenue
- **States & Cities** with the highest revenue
- **Revenue by Category and Sub-Category**
- **Top-performing Products** by revenue
- **Best performing Customer Segments**
- **Region and Shipping Mode performance**

### 📊 **Customer Insights**
- Identified **loyal customers** and **repeat buyers**
- Calculated **Average Revenue per Customer (ARPC)** and **Customer Lifetime Value (CLV)**
- Analyzed **Churn Rate** and **Order Frequency Distribution**
- **Pareto 80/20 Rule Analysis** on revenue contribution

### 📍 **Geographic Insights**
- Top **States and Cities** by the number of orders
- Identified **low-performing states/cities**

### 📅 **Sales & Revenue Trends**
- Monthly and yearly sales trends
- Seasonal fluctuations in sales
- Identified peak and low revenue months

---
## 📈 Superstore Sales Forecasting using SARIMA

This project focuses on building a SARIMA model to forecast future sales based on the Superstore dataset.

### ✅ **Key Highlights**
- Data Cleaning & Preprocessing
- Resampling and Interpolating missing values
- ADF Test for stationarity check
- Hyperparameter tuning using AIC
- SARIMA Model Training & 7-day Sales Forecasting

### 📊 **Tools & Libraries**
- Python, Pandas, NumPy
- Statsmodels (SARIMAX)
- Matplotlib / Seaborn (Optional for visualization)

---

## 📊 Power BI Dashboard Highlights

### ✅ **Key Business Insights**

- **Top Revenue States**: California, New York, and Texas
- **Top Revenue Cities**: Los Angeles, New York City, and Seattle
- **High Revenue Categories**: Technology leads followed by Furniture
- **Top Sub-Categories**: Phones, Chairs, and Copiers
- **Segment & Region Performance**: Consumer Segment & West Region dominate sales
- **Shipping Mode Preference**: Standard Class leads significantly
- **Monthly Sales Trend**: Peaks during November & December, indicating strong year-end sales



## ✅ Conclusion
This project helps uncover meaningful business insights into:
- Customer behavior and segmentation
- Product selling
- Geographic and regional sales performance
- Seasonal and yearly sales trends

---


