Health-Data-Analysis-LMM
Analyzed multi-year health datasets to explore age and race impacts on metabolic and cardiovascular indicators using Linear Mixed Models.

Multi-Year Health Data Analysis Using Linear Mixed Models (LMM)

Project Overview
This project focuses on analyzing multi-year health datasets (ages 34–98) covering demographics, vital signs, and metabolic indicators across multiple sites. The goal was to uncover statistically significant health trends and disparities across age and race groups.

 Data Processing
- Cleaned and preprocessed large-scale datasets covering demographics and health metrics.
- Handled missing values using median imputation and forward-fill techniques.
- Engineered features for metrics like:
  - Resting Diastolic Blood Pressure (DBP)
  - Systolic Blood Pressure (SBP)
  - A1C, BMI, Body Fat, Cholesterol, LDL, HDL, Triglycerides

Analysis Methods
- **Linear Mixed Models (LMM):**
  - Used *Age* as a fixed effect and *Visit ID* as a random effect.
  - Identified statistically significant trends in BP, BMI, LDL, and HDL.
- **Descriptive & Inferential Statistics:**
  - Central tendency, variability, skewness, correlations.
  - Hypothesis testing for significance.
- **Temporal Analysis:**
  - Quarterly trends over 8 years showing seasonal variations.
- **Demographic Insights:**
  - Compared racial groups to identify disparities in BMI, BP, and body composition.

Visualization
Created line plots and bar charts for:
- Age groups vs Health metrics  
- Race vs BMI and BP  
- Yearly and quarterly trends  

Key Insights
- Blood pressure and LDL levels increase significantly with age.  
- HDL levels decline steadily over time, especially among older adults.  
- Distinct racial disparities were observed in BMI and cholesterol profiles.  
- Findings support evidence-based recommendations for personalized health monitoring.

Tools & Technologies
- **Languages:** Python (Pandas, NumPy, Statsmodels, Matplotlib, Seaborn)
- **Statistical Methods:** Linear Mixed Models (LMM), Correlation Analysis, ANOVA
- **Visualization:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

