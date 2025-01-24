# EDA_Python
# Telco Customer Churn Analysis

This repository contains the **Telco Customer Churn Analysis Project**, which aims to analyze customer data to identify churn patterns and develop actionable strategies to reduce churn rates. The project includes exploratory data analysis, predictive modeling, and insights visualization to help telecom companies improve customer retention.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Dataset](#dataset)
- [Project Workflow](#project-workflow)
- [Key Findings](#key-findings)
- [Technologies Used](#technologies-used)
- [Usage Instructions](#usage-instructions)
- [Results](#results)
- [Future Enhancements](#future-enhancements)

---

## Project Overview

Customer churn is a critical metric for telecom companies. This project analyzes customer data to:
- Identify factors contributing to churn.
- Predict churn probability using machine learning.
- Provide actionable recommendations to reduce churn rates.

---

## Objectives
1. Perform in-depth exploratory data analysis (EDA) to understand churn patterns.
2. Visualize key relationships between customer attributes and churn.
3. Train a predictive model to classify churned vs. non-churned customers.
4. Deliver actionable insights to improve customer retention.

---

## Dataset

The dataset used for this project is the **Telco Customer Churn Dataset**, which includes the following features:
- **Demographics**: Gender, Senior Citizen, Partner, Dependents.
- **Services**: Internet Service, Online Security, Tech Support, Streaming TV, etc.
- **Subscription**: Contract type, Paperless Billing, Payment Method.
- **Charges**: Monthly Charges, Total Charges.
- **Churn Indicator**: Whether the customer churned or not.

> **Note**: The dataset is processed to handle missing values, normalize numeric columns, and encode categorical variables.

---

## Project Workflow

1. **Data Cleaning and Preprocessing**:
   - Handled missing values and outliers.
   - Converted `Total Charges` to numeric.
   - Dropped irrelevant columns like `CustomerID` and `Lat Long`.

2. **Exploratory Data Analysis (EDA)**:
   - Churn analysis by demographics, subscription, and service usage.
   - Correlation analysis to identify key predictors.
   - Visualizations using Matplotlib and Seaborn.

3. **Predictive Modeling**:
   - Trained a classification model (e.g., Logistic Regression, Random Forest) to predict churn.
   - Evaluated model performance using accuracy, precision, and recall.

4. **Visualization and Reporting**:
   - Created bar plots, heatmaps, and boxplots to convey insights.
   - Summarized findings in recommendations.

---

## Key Findings
1. **High-Risk Groups**:
   - Customers with month-to-month contracts have a 42.7% churn rate.
   - Electronic check users have the highest churn rate at 45.3%.
2. **Service Impact**:
   - Customers without additional services like Online Security and Tech Support are more likely to churn.
3. **Retention Strategies**:
   - Encouraging long-term contracts and addressing electronic check issues can significantly reduce churn.

---

## Technologies Used
- **Programming**: Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn).
- **Tools**: Jupyter Notebook, Excel.
- **Version Control**: Git and GitHub.

---

## Usage Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/telco-customer-churn.git
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the analysis:
   - Open the Jupyter Notebook `Telco_Customer_Churn_Analysis.ipynb`.
   - Execute the cells step by step to replicate the analysis.

4. Explore the visualizations and model results.

---

## Results
- **Overall Churn Rate**: 26.5%.
- **Key Predictors**: Contract type, Payment Method, Tenure.
- **Model Accuracy**: 85% (Random Forest).

---

## Future Enhancements
1. Implement a dashboard using Tableau or Plotly Dash for real-time insights.
2. Test additional machine learning models for improved prediction.
3. Explore customer segmentation with clustering algorithms.

---

Feel free to contribute or raise issues for improvements!


