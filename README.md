# Car Price Analysis Project

## Overview

Delve into our Car Price Analysis project, where we investigate the multifaceted interplay between variables and car prices. Our mission revolves around identifying the influential factors, understanding their impact, and quantifying their significance on car prices. By leveraging Ordinary Least Squares (OLS) regression, we unlock insights by formulating linear regression equations that establish the nexus between independent variables and the dependent car price. Our analysis embraces both quantitative and categorical variables, enhancing its robustness. This journey takes us through data preprocessing, comprehensive model fitting, rigorous diagnostic checks, and adept model selection.

## Key Steps

1. **Data Preprocessing:**
   - Load and partition data into testing and training sets.
   - Embark on exploratory data analysis, uncovering initial insights.

2. **Model Fitting and ANOVA:**
   - Create a comprehensive model, encompassing various predictor variables.
   - Perform ANOVA type 1, 2, and 3, unraveling variable significance.

3. **Model Diagnosis:**
   - Address assumptions violations in linear regression:
     - Heteroskedasticity
     - Normality of residuals
     - Multicollinearity

4. **Model Selection:**
   - Utilize BIC stepwise model selection to refine the model.
   - Assess predictor relevance and mitigate overfitting.

5. **Result Summarization:**
   - Present a cohesive summary of findings, showcasing impactful variables.

## Final Model

The culminating model is a product of meticulous refinement:
- Notably influential predictors include enginesize, drivewheel, cylindernumber, enginelocation, curbweight, enginetype, carwidth, carbody, aspiration, stroke, peakrpm, boreratio, and wheelbase.
- The model is adeptly optimized, addressing outliers and assumption violations.

## Acknowledgments

This project benefited from the utilization of robust statistical techniques and the supportive data science community. Special thanks to the resources that aided our journey toward a comprehensive understanding of car price determinants.
