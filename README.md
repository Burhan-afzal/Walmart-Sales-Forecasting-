# Walmart-Sales-Forecasting-

**Retail Sales Forecasting Project Report**
1. **Introduction**
Problem Statement
Forecast weekly retail sales to support better inventory and resource management.
Objective
Build a forecasting model to predict weekly sales trends using historical data.

2. **Methodology**
Dataset
•	Source: Walmart Sales Dataset.
•	Target Variable: Weekly_Sales.
Preprocessing
•	Aggregated weekly sales data.
•	Handled missing values in the Date column.
Model
•	SARIMA (Seasonal AutoRegressive Integrated Moving Average): Chosen for its effectiveness in modeling time series data with seasonality.

3. **Results**
Performance Metrics
•	RMSE: 23,412.45 
o	Suitable for applications where large deviations (e.g., inventory planning) can have a significant impact.
•	MAE: 15,230.67 
o	Suitable for applications where all errors are treated equally important.
Visualization
•	The forecasted sales closely follow actual trends, demonstrating the model's effectiveness.

4. **Conclusion**
Observations
•	The model captures general trends and seasonality effectively.
•	Slight discrepancies may occur during high-variability periods.
Recommendations
1.	Incorporate external factors like promotions or competitor actions.
2.	Experiment with other models like Prophet or LSTM for improved accuracy.

**Why Use SARIMA?**
•	Captures Seasonality: SARIMA explicitly incorporates a seasonal component, making it ideal for retail sales data that exhibit recurring patterns (e.g., increased sales during festive seasons or weekends).
SARIMA is a powerful choice for retail sales forecasting due to its ability to handle seasonality effectively, a common feature in retail sales data tied to specific periods such as holidays or weekends.
