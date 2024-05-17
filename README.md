# Prostate Cancer Frailty and Survival Analysis

## Overview
This project explores how different factors affect frailty and survival rates in prostate cancer patients in the UK. Using the Simulacrum synthetic dataset, we apply Binary Logistic Regression (BLR) and Random Forest (RF) models to gain insights and suggest better patient care strategies.

## Objectives
- Examine how demographic factors influence frailty in prostate cancer patients.
- Predict survival rates based on frailty scores and demographic data.
- Develop models to improve patient management in clinical settings.

## Data Source
We used the Simulacrum synthetic dataset developed by Health Data Insight (HDI) with support from AstraZeneca and IQVIA. This dataset simulates real patient data without compromising privacy. 

[Download Simulacrum v2.1.0 (2016-2019 data)](https://simulacrumii201619.s3.eu-west-2.amazonaws.com/simulacrum_v2.1.0.zip)

## Methodology
1. **Data Preparation:**
   - Combine patient and tumor datasets.
   - Filter and clean the data.
   - Create new variables for analysis.
   - Handle missing values.
   - Calculate frailty scores.

2. **Data Analysis:**
   - Use descriptive statistics to explore age, survival status, and frailty scores.
   - Create visualizations to show key metrics.

3. **Modeling:**
   - **Binary Logistic Regression (BLR):** Identify demographic factors affecting frailty.
   - **Random Forest (RF):** Predict survival times using frailty scores and demographic data.

## Key Findings
- **Age:** The main factor affecting frailty and survival outcomes.
- **Protective Factors:** Socio-economic status and certain ethnic backgrounds are linked to lower frailty scores.
- **Model Performance:** High accuracy in predicting frailty and survival rates.

## Implications
- Age and frailty-adjusted treatment plans are crucial for better patient care.
- Personalized healthcare strategies can significantly improve outcomes for prostate cancer patients.

## Future Work
- Validate findings with real patient data.
- Explore long-term studies and interaction effects.
- Compare outcomes across different healthcare settings.

