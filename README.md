# Demand Forecasting & Inventory Insight (Retail Case Study)

## 📌 Business Problem
Retail businesses often struggle to balance product availability and inventory costs due to fluctuating customer demand. This project explores how demand forecasting can support better inventory decisions and reduce the risk of stock-outs and overstocking.

## 📊 Dataset
This project uses a public retail transaction dataset from 2023 containing 1,000 sales records.  
The data includes transaction date, product category, and quantity sold.  
For analysis, transactions were aggregated into **weekly demand at the product category level**.

## 🧠 Approach
1. Exploratory Data Analysis (trend and demand variability)
2. Baseline forecasting: 4-week Moving Average  
3. Advanced models:
   - Exponential Smoothing  
   - ARIMA (1,1,1) and ARIMA (2,1,2)
4. Model evaluation using MAE and RMSE  
5. Business-oriented inventory insights

## 📈 Key Results
- **Clothing** was selected as the main category due to its highest sales volume.
- Weekly demand showed high variability but no clear seasonal pattern.
- Moving Average achieved the lowest numerical error but reacted slowly to demand spikes.
- Exponential Smoothing provided a better balance between responsiveness and stability.

## 📈 Visualizations

![Weekly Demand Trend](figures/weekly_trend_clothing.png)
![Model Comparison](figures/model_comparison.png)

## 📦 Inventory Insights & Recommendations
- Use **Exponential Smoothing** for short-term replenishment planning.
- Keep **Moving Average** as a simple strategic benchmark.
- Closely monitor high-demand weeks to mitigate stock-out risk.

## 🛠️ Requirements
See `requirements.txt`
