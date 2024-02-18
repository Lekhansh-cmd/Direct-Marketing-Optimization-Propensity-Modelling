# Direct Marketing Optimization

## Task
The objective of this project is to maximize revenue from direct marketing campaigns using dummy data. The key tasks involved include creating analytical datasets, developing propensity models, and optimizing targeting clients with direct marketing offers.

## Data
For the analysis, several tables are available:
 Social-demographical data (age, gender, tenure in a bank)
 Products owned + actual volumes (current account, savings account, mutual funds, overdraft,
credit card, consumer loan)
 Inflow/outflow on C/A, aggregated card turnover (monthly average over past 3 months)
 For 60 % of clients, actual sales + revenues from these are available (training set)

## Conditions:
 The bank can contact only 15 pct. of the clients (cca 100 people) with a marketing offer and each client can be targeted only once.

## Proposed Steps
1. **Create Analytical Dataset**: Merge and preprocess various data tables to create training and targeting datasets.
2. **Develop Propensity Models**: Build three propensity models for predicting consumer loans, credit cards, and mutual fund purchases using the training dataset.
3. **Optimize Targeting**: Identify clients with higher propensities for each offer and optimize targeting to maximize revenue.

## Expected Result
The project aims to answer the following questions:
- Which clients have a higher propensity to buy consumer loans, credit cards, or mutual funds?
- Which clients should be targeted with each offer?
- What would be the expected revenue based on the targeting strategy?

## Executive Summary
This report provides insights into the analysis conducted for direct marketing optimization. It covers the objective, technology used, analysis steps, model evaluation, revenue prediction, and expected results. The key findings include the accuracy of propensity models, identification of targeted clients, and expected revenues from marketing offers.

### Technology Used
- Jupyter Notebook
- Python Libraries: scikit-learn, pandas, numpy, matplotlib

### Analysis Steps
1. **Data Preparation**: Merge, preprocess, and handle missing values.
2. **Propensity Model Development**: Develop models for consumer loans, credit cards, and mutual fund purchases.
3. **Model Evaluation**: Evaluate models using training and testing datasets.
4. **Revenue Prediction and Targeting**: Calculate propensity scores and predict revenue for each marketing offer.
5. **Results**: Analyze accuracy scores, RMSE, and expected revenues for targeted clients.

Overall, this project provides valuable insights into maximizing revenue through targeted direct marketing efforts based on customer propensity scores.
