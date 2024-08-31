# Walmart Black Friday Customer Analysis

## Overview

This project analyzes customer purchase behavior at Walmart during Black Friday, focusing on the differences in spending habits between male and female customers. Additionally, the analysis explores the impact of marital status and age on purchase amounts. The goal is to provide actionable insights for Walmart's management to make data-driven business decisions.

## Dataset Description

The dataset includes transactional data of customers who purchased products from Walmart stores during Black Friday. It contains the following features:

- **User_ID**: Unique identifier for each customer.
- **Product_ID**: Unique identifier for each product.
- **Gender**: Customer's gender (Male or Female).
- **Age**: Age group of the customer (in bins).
- **Occupation**: Masked occupation identifier.
- **City_Category**: Category of the city where the customer resides (A, B, C).
- **StayInCurrentCityYears**: Number of years the customer has stayed in the current city.
- **Marital_Status**: Marital status of the customer (Single or Partnered).
- **ProductCategory**: Masked product category identifier.
- **Purchase**: Purchase amount.

## Project Objectives

1. **Gender-Based Spending Analysis**:
   - Determine if women spend more on Black Friday than men.
   - Compute average spending per transaction for male and female customers.
   - Analyze the confidence intervals for male and female spending.

2. **Marital Status and Age-Based Analysis**:
   - Analyze the spending behavior of married vs. unmarried customers.
   - Explore the spending patterns across different age groups.

3. **Confidence Interval Calculation**:
   - Use the Central Limit Theorem (CLT) to compute confidence intervals for average spending.
   - Evaluate if the confidence intervals for different groups (gender, marital status, age) overlap.

4. **Business Insights and Recommendations**:
   - Generate insights based on the analysis to help Walmart enhance its marketing and sales strategies.

## Analysis Approach

1. **Data Exploration**:
   - Import the dataset and perform an initial exploration to understand the structure, data types, and characteristics.
   - Identify and handle any missing values and outliers.

2. **Gender-Based Spending Analysis**:
   - Track the amount spent per transaction for male and female customers.
   - Compute and compare the average spending for both genders.
   - Use confidence intervals to estimate the population mean for male and female spending.

3. **Marital Status and Age-Based Analysis**:
   - Perform similar spending analysis for married vs. unmarried customers and across different age groups.
   - Compute confidence intervals and analyze the overlap.

4. **Statistical Analysis**:
   - Use the Central Limit Theorem to compute confidence intervals.
   - Experiment with different confidence levels (90%, 95%, 99%) and observe their impact on the interval width.

5. **Visualization**:
   - Visualize the data using various plots (distplots, boxplots, heatmaps, etc.) to better understand the relationships between variables.

6. **Business Insights**:
   - Summarize key findings from the analysis and how Walmart can leverage these insights.

7. **Recommendations**:
   - Provide actionable recommendations based on the analysis to improve Walmart's business strategies.

😇 Please do check the code and let me know if any changes required to make it better. 🤞🤞

⚡⚡ Thank you in advance for visiting and reviewing the code. 🙌😎
