**Capstone Project - Fall 2024**

# Swire Coca-Cola Predictive-Maintenance-Project
This repository contains the Swire Coca-Cola Predictive Maintenance Project for Group 2.

---

## Team Members
- Richard Lim
- Ketki Kulkarni
- Anusha Vivekanand
- Vedika Garg

---

## Introduction
In terms of food & beverage industry, the production efficiency is key to keep competitive position in the market. 

For Swire Coca-Cola, one of the world’s largest beaverage corportate, machine downtime isn’t just a technical challenge, which causes a $60 million annual loss. To tackle this problem, our capstone project focused on improving the company’s maintenance operations with predictive analytics.

By analyzing machine performance data, we identified the breakdown patterns to predict equipment failure occurences and optimize maintenance schedules based on the patterns. This proactive approach minimizes unplanned breakdowns, streamlines the smooth production, lowers the wastesd costs, and improves overall efficiency. Our work highlights how data-driven approaches can turn log data into actionable results, creating a stronger, more reliable manufacturing process.

---

## Business Problem
Swire Coca-Cola’s six manufacturing plants produce a staggering 192 million beverages annually. 

However, unplanned machine breakdowns have brought production capacity down to 94.4%, causing substantial delays and financial losses. These unpredictable failures result in frequent downtime, missed production targets, and increased costs, amounting to an estimated $60 million in annual losses. 

Therefore, it is essential to maintain production goals and profitability by addressing the issue and find out resolution.

---

## Proposed Solution
Our solution focuses on survival analysis applied to unplanned downtime data, enabling the prediction of time-to-failure before critical equipment failure occurs. 

Using predictive models, we can allocate maintenance schedules tailored to minimize unplanned operational disruptions. 

This approach empowers Swire Coca-Cola to anticipate failures, reduce operational downtime, and optimize maintenance resources, thereby improving production capacity and reducing costs.

---

## Model Performance Highlights
Among the multiple variations of regression model, The ElasticNet regression model demonstrated superior predictive performance, achieving:

- Test RMSE: 82.27
- Test MSE: 6767.92

This model effectively balances bias and variance, making it a reliable choice for predicting maintenance outcomes and optimizing operations.



---
## Key Insights from Survival Analysis

- Conducted Kaplan-Meier survival estimates to predict the duration of equipment time-to-failure.
- Filtered and concentrated on unplanned downtime data to identify trends and probabilities of machine breakdowns.
- LogRank tests were conducted as a part of robustness checks to validate the survival analysis results

Our survival analysis revealed the following average failure times for equipment at key plant locations:

- Roma (G812): Equipment fails, on average, within 0.47 days.
- Cota (G816): Average failure time is 0.65 days.
- Suzuka (G221): Equipment tends to fail after 1.24 days.

These insights provide actionable recommendations for proactive maintenance, helping reduce unplanned downtime across locations.

---

## Analytics Approach

### Data Preprocessing
- Cleaned and structured performance data, including machine runtime, temperature, and vibration metrics.
- Addressed missing values and outliers to ensure reliable model training.

### Survival Analysis
- Conducted Kaplan-Meier survival estimates to predict the duration of equipment time-to-failure.
- Filtered and concentrated on unplanned downtime data to identify trends and probabilities of machine breakdowns.
- LogRank tests were conducted as a part of robustness checks to validate the survival analysis results

### Regression Modeling
- Built supervised regression models to predict downtime durations, achieving an RMSE of 82.27.
- Implemented hyperparameter tuning to optimize the predictive performance metrics.

### Feature Engineering and Evaluation
- Created the new variables such as rolling averages and lag features to increase prediction accuracy.
- Evaluated model performance using error metrics and validated survival analysis outputs.

---

## Scope
### In Scope
- Predictive analytics for unplanned downtime.
- Equipment performance dashboards.
- Recommendations for spare parts inventory optimization.

### Out of Scope
- Analysis of planned maintenance activities.
- Direct measurement of financial savings.

### Future Additions
- Integration of IoT sensors for real-time tracking.
- Automated maintenance workflows powered by predictive analytics.


---
## Key Outcomes:

### Accurate Predictive Models: 
Survival analysis achieved a C-index of 0.85, while regression models attained a test RMSE of 0.72 days, providing reliable failure and downtime predictions.

### Operational Improvements:
The insights from our models facilitated targeted maintenance planning, with a focus on high-risk locations and frequently failing equipment, enhancing operational efficiency.

### Actionable Insights: 
We provided clear recommendations for optimized maintenance schedules and spare part inventory management, ensuring effective resource allocation and significant downtime reduction.

These results demonstrate how predictive analytics can revolutionize maintenance operations, reducing financial losses and bolstering production resilience. we think this project serves as a valuable reference for leveraging advanced analytics to address critical challenges in manufacturing processes.

---

## Conclusion and Summary

Our project highlights the critical role of data-driven maintenance strategies in addressing operational inefficiencies at Swire Coca-Cola. By leveraging survival analysis and regression models, we developed tools to forecast equipment failures and proactively reduce unplanned downtime, leading to improved production efficiency.


