# Logistics Delivery Performance Analysis & Late-Delivery Risk Prediction

## Project Overview
This project analyses supply-chain delivery performance using the public DataCo Smart Supply Chain dataset. The objective is to understand delivery-status patterns, compare shipping modes, identify factors associated with late-delivery risk, and establish a foundation for predictive analysis.

## Business Problem
Delivery delays can affect customer satisfaction and operational planning. This project uses historical data to investigate delivery performance and explore whether late-delivery risk can be estimated using suitable information available before the delivery outcome.

## Dataset
- **Source:** [DataCo Smart Supply Chain Dataset — Mendeley Data](https://data.mendeley.com/datasets/8gx2fvg2k6/5)
- **Rows initially observed:** 180,519
- **Columns initially observed:** 53
- **Unique orders:** 65,752
- **Unique customers:** 20,652

The dataset contains order, product, shipping, delivery-status, and other supply-chain information. The original dataset is not included in this repository because it contains customer-related information.

## Initial Findings
- Late delivery: 98,977 records.
- Advance shipping: 41,592 records.
- Shipping on time: 32,196 records.
- Shipping canceled: 7,754 records.
- First Class showed a 95% observed late-risk rate, while Standard Class showed 38%.

These are preliminary record-level findings and do not establish causation.

## Key Performance Indicators
1. Late-delivery risk rate.
2. On-time and advance-shipping share.
3. Actual versus scheduled shipping duration.
4. Number of unique orders analysed.

## Tools and Methods
- Python
- Pandas
- Matplotlib
- Exploratory Data Analysis
- Data preprocessing
- Classification and model evaluation (planned)

## Project Roadmap
- **Week 1:** Strategic planning, business problem, dataset review, KPIs, and project roadmap.
- **Week 2:** Data quality assessment and preprocessing.
- **Week 3:** Exploratory data analysis and visualizations.
- **Week 4:** Predictive modelling, evaluation, and recommendations.

## Important Limitation
The dataset contains multiple item-level records per order. Predictive modelling must avoid data leakage by excluding variables that reveal the delivery outcome.

## Status
Week 1 — Strategic planning and initial dataset review.

