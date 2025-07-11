# Store Inventory Demand Analysis & Optimization

![Project Banner](./project-banner.jpg)

This project presents a comprehensive solution to manage inventory risk and optimize operational performance using data-driven forecasting, real-time monitoring, and automated decision systems. Though focused on the healthcare supply chain, the approach and techniques are directly applicable to risk management, credit strategy, and portfolio monitoring in digital lending.

---

## Tools & Technologies Used

- **SQL** – Automated risk flagging & alert systems  
- **Python** – Forecasting model development & data preprocessing  
- **Power BI** – Real-time monitoring dashboards  
- **Excel** – Data cleaning and historical trend reports  
- **Forecasting Techniques** – ARIMA, Holt-Winters, VECM  
- **Machine Learning** – Random Forest Regression

---

## Project Objectives Aligned with Risk & Portfolio Mgmt.

- **Minimize Operational Risk**: Forecast demand accurately to avoid shortages, acting as an analogue for predicting credit default or high-risk borrowers.
- **Enable Real-Time Alerts**: SQL-driven triggers flag deviations in expected stock levels — similar to portfolio risk flags or early warning systems in credit portfolios.
- **Automate Decision Workflows**: Designed rule-based thresholds and modeled reorder logic — equivalent to credit strategy execution (e.g., line assignment, eligibility rules).
- **Support Data-Driven Strategy**: Insights powered by modeling informed dynamic inventory planning — similar to customer segmentation and strategy testing in digital lending.

---

## Key Achievements

- Built predictive models (Random Forest, ARIMA) with MAPE <10%, minimizing shortages and enhancing service reliability.
- Developed automated stock alert systems using SQL queries, simulating risk flagging frameworks used in credit monitoring.
- Created a real-time Power BI dashboard to visualize and track stock performance — analogous to a lending portfolio dashboard.
- Defined reorder strategies through forecasting, improving efficiency and reducing manual interventions — reflecting credit line optimization strategies.

---

## Technical Overview

### Forecasting & Risk Modeling

Used a combination of statistical and machine learning models to simulate demand behavior and identify high-risk scenarios (stockouts), much like early-stage credit default identification.

| Model               | Metric       | Score    |
|--------------------|--------------|----------|
| Random Forest       | MSE          | 111.61   |
| Holt-Winters        | RMSE         | 5032.71  |
| Linear Regression   | MSE          | 159.58   |

Random Forest demonstrated strong predictive power and robustness to outliers, similar to capturing borrower behavioral patterns.

---

## Portfolio Monitoring & Alerts (Simulated)

- Created **SQL-based inventory flags** that emulate borrower risk alerts.
- Built a Power BI dashboard that functions like a **portfolio performance monitoring tool**, providing insights into consumption, shortages, and demand trends.

---

## Data Preprocessing

- Cleaned, transformed, and normalized large historical datasets for modeling.
- Engineered lag and rolling average features to enhance time-series and regression models.
- Applied log transformation to address skewed demand — similar to income normalization in borrower risk modeling.

---

## Project Challenges

- **Return Quantity Prediction**: Similar to predicting irregular customer repayment behavior.
- **External Disruption Modeling**: Handled demand shifts due to health events — transferable to market-driven credit risks.
- **Data Integration**: Ensured clean, usable inputs from multiple sources, akin to working with telecom, mobile wallet, or bureau data in credit modeling.

---

## Future Enhancements

- Apply advanced ML models (e.g., XGBoost, LSTM) to simulate complex borrower behavior.
- Integrate real-time external data feeds for dynamic strategy updates (like bureau updates or telecom usage).
- Extend real-time alerting and segmentation to customer-level decisioning — enabling lending strategy A/B testing or credit line reassignment.

---

