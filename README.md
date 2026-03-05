# Customer Segmentation & Customer LifeTime Value (CLTV) Modeling for Flo E-commerce

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Power BI](https://img.shields.io/badge/Power_BI-Dashboard-yellow.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data_Manipulation-lightgrey.svg)
![Machine Learning](https://img.shields.io/badge/Machine_Learning-Predictive_Analytics-success.svg)

## 📌 Project Overview
This project is an end-to-end Data Science and Business Intelligence solution designed to optimize the CRM strategy for an e-commerce platform. By analyzing omnichannel customer behavior data (20,000+ rows, 10+ features), this project bridges the gap between raw data and actionable business decisions. 

The primary objectives are to automatically segment customers, predict potential churners, and estimate the Customer Lifetime Value (CLTV) to maximize retention and marketing ROI.

## 🚀 Key Highlights & Business Value
- **Actionable Segmentation:** Performed RFM analysis and **K-Means clustering** to segment customers into actionable cohorts (e.g., Champions, At-Risk, Loyal Customers).
- **Targeted Marketing Campaigns:** Extracted highly specific customer IDs for direct marketing (e.g., Targeting "Champions" for a new premium women's shoe brand, and "At-Risk/Sleeping" customers for a 40% discount campaign).
- **High-Precision Churn Prediction:** Developed a **Logistic Regression** model achieving **93% Precision** in predicting customer churn, ensuring retention budgets are spent on the right audience.
- **Accurate CLTV Forecasting:** Built a **Random Forest Regressor** to predict 2-year customer lifetime value, achieving an outstanding **0.99 R² Score**, explaining almost all variance in future customer spending.
- **Executive Dashboarding:** Exported predictive insights into **Power BI** to build interactive dashboards visualizing loyalty trends, churn risks by channel, and predicted revenue.

## 🛠️ Methodology & Tech Stack

### 1. Data Engineering & Preprocessing (Pandas)
- Handled missing values, outliers, and data type conversions.
- Engineered new omnichannel features (combining online and offline metrics) such as `total_order_num` and `total_customer_value`.

### 2. Rule-Based Customer Segmentation
- Calculated Recency, Frequency, and Monetary (RFM) metrics.
- Applied regex-based mapping to categorize customers into 10 distinct business segments.

### 3. Predictive Modeling (scikit-learn)
- **Clustering:** `KMeans` algorithm to find hidden patterns within RFM metrics.
- **Classification (Churn):** `LogisticRegression` to classify whether a customer will churn (>90 days inactive).
  - *Metrics:* 77% Accuracy | 93% Precision for Churn class.
- **Regression (CLTV):** `RandomForestRegressor` to predict the exact monetary value a customer will bring over a 24-month lifespan.
  - *Metrics:* 0.99 R² Score | 1143 RMSE.


### 4. Business Intelligence (Power BI)
<img width="1314" height="736" alt="Flo Project Dashboard" src="https://github.com/user-attachments/assets/18cd5fb1-82b0-4791-93d2-091d6b4986f2" />

- Consolidated all model predictions and segmentation labels into a clean `.csv` dataset.
- Created interactive dashboards to inform data-driven marketing campaigns.

## 📂 Project Structure
- `FLO_PROJE.ipynb`: The main Jupyter Notebook containing all data cleaning, EDA, feature engineering, and machine learning pipelines.
- `FLO_PowerBI_Dataset.csv`: The finalized dataset exported for Power BI visualization.
- `yeni_kadin_markasi_hedef.csv` / `erkek_cocuk_indirim_hedef.csv`: Output lists of targeted customer IDs for specific marketing scenarios.

## 📬 Contact
**Erdem Yavuz Hacisoftaoglu** 📧 Email: erdemyavuz.hacisoftaoglu@gmail.com  
💼 LinkedIn: https://www.linkedin.com/in/erdem-yavuz-hacisoftaoglu/
