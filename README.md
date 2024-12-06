**Capstone Project - Fall 2024**
# Group 2 -Swire Coca-Cola (Predictive-Maintenance-Project)
This repository contains the Swire Coca-Cola Predictive Maintenance Project.


---

## Introduction
In today’s highly competitive beverage industry, operational efficiency is critical to maintaining market leadership. For Swire Coca-Cola, one of the largest bottlers in the world, machine downtime is more than just a technical issue—it’s a $60 million annual setback. Recognizing the urgency of this problem, our project aimed to revolutionize the company’s maintenance operations using predictive analytics.

By leveraging machine performance data, we analyzed patterns that could forecast equipment failures and optimize maintenance schedules. This proactive approach not only addresses unplanned breakdowns but also ensures smoother production cycles, reduced costs, and higher operational efficiency. Our work demonstrates how data-driven strategies can bridge the gap between innovation and execution, paving the way for a more resilient manufacturing process.

---

## Business Problem
Swire Coca-Cola’s six manufacturing plants produce a staggering 192 million beverages annually. However, unplanned machine breakdowns have brought production capacity down to 94.4%, causing substantial delays and financial losses. These unpredictable failures result in frequent downtime, missed production targets, and increased costs, amounting to an estimated $60 million in annual losses. Addressing this issue is essential to maintain production goals and profitability.

---

## Proposed Solution
Our solution focuses on survival analysis techniques applied to unplanned downtime data, enabling the prediction of time-to-failure for critical equipment. Using predictive models and actionable insights, we proposed maintenance schedules tailored to minimize disruptions. This approach empowers Swire Coca-Cola to anticipate failures, reduce operational downtime, and optimize maintenance resources, thereby improving production capacity and reducing costs.

---

## Model Performance Highlights
The ElasticNet model demonstrated superior predictive performance, achieving:

Test RMSE: 82.27
Test MSE: 6767.92
This model effectively balances bias and variance, making it a reliable choice for predicting maintenance outcomes and optimizing operations.

---
## Key Insights from Survival Analysis
Our survival analysis revealed the following average failure times for equipment at key plant locations:

Roma (G812): Equipment fails, on average, within 0.47 days.
Cota (G816): Average failure time is 0.65 days.
Suzuka (G221): Equipment tends to fail after 1.24 days.
These insights provide actionable recommendations for preemptive maintenance, helping reduce unplanned downtime across locations.

---

## Analytics Approach

### Data Preprocessing
- Cleaned and structured performance data, including machine runtime, temperature, and vibration metrics.
- Addressed missing values and outliers to ensure reliable model training.

### Survival Analysis
- Conducted Kaplan-Meier survival estimates to predict equipment time-to-failure.
- Analyzed unplanned downtime data to identify trends and probabilities of machine breakdowns.

### Regression Modeling
- Built supervised regression models to predict downtime durations, achieving an RMSE of 0.72 days.
- Implemented hyperparameter tuning to optimize predictive performance.

### Feature Engineering and Evaluation
- Created rolling averages and lag features to enhance prediction accuracy.
- Evaluated model performance using error metrics and survival analysis outputs.

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
## Conclusion and Summary

Our project highlights the critical role of data-driven maintenance strategies in addressing operational inefficiencies at Swire Coca-Cola. By leveraging survival analysis and regression models, we developed tools to forecast equipment failures and proactively reduce unplanned downtime, leading to improved production efficiency.

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

## Team Members
- Richard Lim
- Ketki Kulkarni
- Anusha Vivekanand
- Vedika Garg


