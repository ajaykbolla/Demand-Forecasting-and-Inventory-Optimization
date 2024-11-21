# Demand-forecasting-and-inventory-optimization

## Table of Contents
1. Project Background
1. Problem Statement/Objective
2. Executive Summary
3. Data
5. Methodlogy
6. Results
4. Deep dive insights
5. Business Impact
9. Strategy/Recommendations
10. Assumptions and Limitations
11. Future Scope
12. Conclusion



## Project Background

Effective inventory management and accurate demand forecasting are crucial for business success. Inefficient inventory practices can lead to stockouts and excess inventory, while inaccurate forecasts can result in lost sales and reduced customer satisfaction.

This project aims to address these challenges by developing a system that:

Improves Demand Forecasting: Utilizes advanced forecasting techniques to accurately predict future demand.
Optimizes Inventory Levels: Employs optimization algorithms to determine optimal stock levels.
Enhances Supply Chain Efficiency: Streamlines supply chain operations for timely and accurate demand fulfillment.
Boosts Customer Satisfaction: Ensures product availability and timely delivery to meet customer needs.


## Problem Statement

In supply chain management, forecasting demand and optimizing inventory are essential for operational efficiency and customer satisfaction. As a data analyst, I used **time series** analysis to predict future sales of Product P1 and calculate **safety stock** to manage demand variability. I determined the **reorder point** to signal when inventory replenishment was needed, ensuring adequate stock without overstocking or understocking. Additionally, I applied the **Economic Order Quantity (EOQ)** model to identify the optimal order quantity that minimizes inventory costs. Finally, I established the **reorder cycle**, defining the time interval for placing orders to maintain seamless inventory management.


## Executive Summary
The analysis aimed to forecast the demand for Product P1 and optimize inventory processes. Using time series analysis, future demand was predicted, and safety stock levels were calculated to account for demand fluctuations. Key metrics, such as the reorder point (258.15 units), optimal order quantity (133 units), and total inventory cost (556.65 units), were determined. These insights enable cost-efficient inventory management while minimizing stockouts and overstocking risks.



## Data

The dataset used contained 62 daily records for Product P1, including:

Date: Daily timestamps.
Product_ID: Identifier for the product (P1).
Demand: Daily demand for Product P1.
Inventory: Available inventory on a given day.
1st_diff_demand: First-order differences to analyze demand trends.
The data ranged from June 1, 2023, to August 1, 2023, with inferred daily frequency.


## Methodology

Stationarity Testing:

The Augmented Dickey-Fuller (ADF) test was conducted to check stationarity. The test statistic was -7.52, and the p-value was 3.84e-11, confirming stationarity.
Time Series Forecasting:

A predictive model was developed to forecast demand for the next 10 days (August 2–11, 2023).
Inventory Optimization:

Safety Stock Calculation: Based on demand variability and lead time.
Reorder Point Calculation: Combined lead time demand and safety stock.
Economic Order Quantity (EOQ): Computed to minimize holding and ordering costs.
Cost Analysis:

The total inventory cost was evaluated, incorporating EOQ and safety stock levels.


## Results
Forecasted Demand (August 2–11, 2023):

Demand ranged between 114–130 units/day, with a steady trend.
Optimal Metrics:

Reorder Point: 258.15 units.
Optimal Order Quantity (EOQ): 133 units.
Total Inventory Cost: 556.65 units.

## Deep Dive insights

The forecast suggests consistent demand, enabling predictable inventory planning.
The reorder point ensures timely replenishment, reducing risks of stockouts.
The EOQ model balances holding and ordering costs, making inventory management cost-efficient.

## 7. Business Impact
Reduced risk of inventory shortages and overstocking.
Optimized inventory levels improve cash flow and operational efficiency.
Improved customer satisfaction due to better product availability.

## 8. Strategy/Recommendations
Implement the reorder point and EOQ model to automate inventory management for Product P1.
Monitor demand fluctuations and adjust safety stock levels periodically.
Conduct similar analyses for other products to standardize inventory processes across the supply chain.

## 9. Assumptions and Limitations
Assumptions:
Demand follows historical trends without unexpected spikes.
Lead time and ordering costs remain constant.
Limitations:
Short dataset duration (62 days) may not fully capture seasonal demand patterns.
Assumed stationarity may not account for long-term trends or shocks.

## 10. Future Scope
Extend the dataset to include multiple products and longer timeframes for better insights.
Incorporate advanced forecasting models (e.g., ARIMA, LSTM) for improved accuracy.
Explore dynamic safety stock calculations based on real-time data.


## 11. Conclusion
This analysis provides a robust framework for demand forecasting and inventory optimization for Product P1. By leveraging time series analysis and the EOQ model, the supply chain team can achieve cost-efficient inventory management while maintaining product availability.


