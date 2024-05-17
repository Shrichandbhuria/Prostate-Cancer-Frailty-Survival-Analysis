# Prostate-Cancer-Frailty-Survival-Analysis
Analyzing demographic influences on frailty and survival in UK prostate cancer patients using synthetic data.


# Prostate Cancer Frailty and Survival Analysis

## Overview
This project aims to analyze the impact of demographic and clinical factors on frailty and survival rates among prostate cancer patients in the UK. Using the Simulacrum synthetic dataset, we employ Binary Logistic Regression (BLR) and Random Forest (RF) models to derive key insights and provide actionable recommendations for personalized patient care.

## Objectives
- Analyze demographic factors influencing frailty in prostate cancer patients.
- Predict overall survival rates based on frailty scores and demographic data.
- Develop models to enhance patient management strategies in clinical settings.

## Data Source
The dataset used in this analysis is the Simulacrum synthetic dataset, developed by Health Data Insight (HDI) with support from AstraZeneca and IQVIA. It simulates real patient data without compromising individual privacy.

## Methodology
1. **Data Preparation:**
   - Merging patient and tumor datasets.
   - Filtering and cleaning data.
   - Creating new variables for analysis.
   - Handling missing values and data imputation.
   - Calculating frailty scores.

2. **Data Analysis:**
   - Descriptive statistics to explore age, survival status, and frailty scores.
   - Visualizations to illustrate key metrics.

3. **Modeling:**
   - **Binary Logistic Regression (BLR):** To identify key demographic factors affecting frailty.
   - **Random Forest (RF):** To predict overall survival times based on frailty scores and demographic data.

## Key Findings
- **Age:** The primary predictor of frailty and survival outcomes.
- **Protective Factors:** Socio-economic status and certain ethnic backgrounds are associated with lower frailty scores.
- **Model Performance:** High accuracy in predicting frailty and survival rates.

## Implications
- Age and frailty-adjusted treatment plans are crucial for effective patient care.
- Personalized healthcare strategies can significantly improve outcomes for prostate cancer patients.

## Future Work
- Validate findings with real patient data.
- Explore longitudinal studies and interaction effects.
- Conduct comparative studies across different healthcare settings.

