# Life Expectancy Analysis

## Overview
This project analyzes **global life expectancy trends** and identifies key factors affecting health outcomes. The dataset includes country-wise data on **economic, health, and demographic indicators** such as **GDP, healthcare spending, schooling, and mortality rates**. The goal is to uncover patterns and provide insights to policymakers for improving public health strategies.

## Steps Taken
1. **Data Cleaning** – Handled missing values using **KNN Imputation**, removed outliers using the **IQR method**, and standardized features.
2. **Exploratory Data Analysis (EDA)** – Identified key correlations, such as:
   - **Life expectancy (-0.69 correlation with adult mortality)**
   - **Strong positive correlation (+0.57) with BMI and schooling**
3. **Predictive Modeling** – Used **Linear Regression** to predict life expectancy, achieving an **R² score of 0.73**.
4. **Clustering Analysis** – Categorized countries into **developed, developing, and underdeveloped** based on GDP and health indicators.

## Key Insights
- **Higher GDP and schooling levels lead to increased life expectancy**.
- **Developing countries show slower improvements**, indicating the need for better healthcare investments.
- **Health policies must focus on reducing mortality rates and increasing healthcare accessibility**.


