# Exploring the Correlation between Development Indicators and Happiness

## Overview
This project, completed as part of the *Mathematical Statistics* course at *Bocconi University*, was conducted in collaboration with @makuleprohaska. The study investigates whether **social or economic indicators** are more relevant in predicting national happiness, using **multivariate linear regression** and statistical hypothesis testing.

## Key Findings
- **GDP per capita** and **life expectancy** showed the strongest positive correlation with happiness.
- **Current account and inflation** had little to no predictive power.
- A **two-sample t-test** found no statistically significant difference between economic and social indicators in explaining happiness (*p-value = 0.4368*).
- Model selection techniques (step-up, step-down, stepwise) identified a **simplified regression model** that performed slightly better by excluding inflation and current account variables.
- Regression models explained **73-77% of the variance** in happiness levels across countries.

## Methodology
- **Data from 94 countries (2016-2021)** covering 8 development indicators (4 social, 4 economic).
- **Data preprocessing**, including normalization and handling missing values.
- **Exploratory Data Analysis (EDA)** with scatter plots to visualize correlations.
- **Model diagnostics** to check regression assumptions (normality, homoscedasticity).

## Conclusion
Happiness is influenced by both economic and social factors, but the relative importance of each depends on the indicators chosen. While GDP per capita and life expectancy are strong predictors, the exclusion of specific indicators can alter conclusions. 

For a detailed breakdown of our findings and methodology, refer to the **full report in this repository**.

