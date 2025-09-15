# Twitter Suspensions After the 2020 Election

## Overview
Analyzes Twitter account suspensions post-2020 U.S. Presidential Election, focusing on whether Trump vs. Biden hashtags correlate with suspension rates.

## Data
- **File:** `mosleh_et_al_data.csv`  
- **Columns:** `politics_hashtag` (1 = Trump, 0 = Biden), `suspended` (1 = yes, 0 = no), user features  

## Methods
- Crosstabs & visualizations  
- Odds ratios & chi-square tests  
- t-tests, z-scores  
- Probit & Logit regressions  
- ROC/AUC evaluation  

## Findings
- Trump-hashtag accounts more likely suspended  
- Association statistically significant  
- Regression confirms robustness  

## Requirements
```bash
pip install pandas numpy matplotlib seaborn scipy statsmodels scikit-learn
