# Term Deposit Marketing
## Overview
This project aims to develop a machine learning system for predicting customer subscription to term deposits based on call center data from a European banking institution. The system will improve the success rate of marketing calls and provide interpretability for clients to make informed decisions.

## Background and Motivation
We are a small startup specializing in machine learning solutions for the European banking market, tackling challenges like fraud detection, sentiment classification, and customer intention prediction. Our current focus is on building a robust machine learning product that leverages call center data to enhance the effectiveness of direct marketing efforts. Our goal is to create an evolving system that not only delivers high success rates but also offers transparency, helping our clients better understand the factors driving customer decisions.

## Goals
1. **Primary Goal:** Predict whether a customer will subscribe to a term deposit (binary classification).
2. **Success Metric:** Achieve 81% or higher accuracy using 5-fold cross-validation.
3. **Secondary Goals:**
   - Identify customer segments more likely to purchase the investment product.
   - Determine key features that influence customer decisions.

## Datasets
- **Source:** Direct marketing data from a European banking institution.
- **Features:**
  - `age`: Age of the customer (numeric)
  - `job`: Type of job (categorical)
  - `marital`: Marital status (categorical)
  - `education`: Education level (categorical)
  - `default`: Credit in default? (binary)
  - `balance`: Average yearly balance, in euros (numeric)
  - `housing`: Has a housing loan? (binary)
  - `loan`: Has a personal loan? (binary)
  - `contact`: Contact communication type (categorical)
  - `day`: Last contact day of the month (numeric)
  - `month`: Last contact month of the year (categorical)
  - `duration`: Last contact duration, in seconds (numeric)
  - `campaign`: Number of contacts during the campaign (numeric)
- **Target:**
  - `y:` Customer subscription to a term deposit (binary)

## Milestones
1. **Data Exploration:** Understand the dataset, perform initial cleaning, and visualize key features.
2. **Model Development:** Train and validate machine learning models, aiming for an accuracy of 81% or higher.
3. **Feature Importance Analysis:** Identify which features most strongly influence customer decisions.
4. **Customer Segmentation:** Develop strategies to prioritize customers most likely to subscribe to the product.
5. **Final Report:** Summarize findings, model performance, and provide actionable insights for clients.


















