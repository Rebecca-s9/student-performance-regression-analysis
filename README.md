# Student Performance Factors: Regression and Statistical Inference Analysis

## Project Overview

This project investigates factors associated with student academic performance using exploratory data analysis and multiple linear regression.

The goal is not only to build a predictive model, but also to interpret coefficients, evaluate statistical significance, examine confidence intervals, check model assumptions, and discuss limitations.

## Dataset

The dataset contains 6,607 student records with academic, behavioral, socioeconomic, and school-related variables.

The target variable is:

- `Exam_Score`

Predictors include:

- Hours studied
- Attendance
- Sleep hours
- Previous scores
- Tutoring sessions
- Motivation level
- Parental involvement
- Access to resources
- Family income
- Teacher quality
- Peer influence
- Learning disabilities
- Distance from home
- Gender

## Methods

This project applies:

- Exploratory data analysis
- Correlation analysis
- Multiple linear regression
- Statistical inference using p-values and confidence intervals
- Standardized coefficient analysis
- Residual diagnostics
- Variance Inflation Factor analysis for multicollinearity

## Key Results

The final multiple linear regression model explained approximately 72.7% of the variation in exam scores.

The strongest positive predictors included:

- Attendance
- Hours studied
- Previous scores
- Tutoring sessions
- Positive peer influence

The strongest negative predictors included:

- Low access to resources
- Low parental involvement
- Low family income
- Low motivation level
- Low teacher quality
- Learning disabilities

Standardized coefficients suggested that attendance was the strongest positive predictor, while low access to resources and low parental involvement were among the strongest negative predictors.

## Model Diagnostics

Residual diagnostics showed that the model captures the main structure of the data reasonably well. However, the Q-Q plot showed deviations from normality in the upper tail, caused by several unusually large positive residuals.

Influence analysis suggested that these unusual observations did not dominate the overall regression results based on Cook's distance.

## Limitations

This analysis is observational, so the results should be interpreted as associations rather than causal effects.

Some important factors may be missing from the dataset, such as study quality, individual ability, school environment, exam difficulty, mental health, or learning strategies.

Missing categorical values were imputed using the mode, which allowed the full dataset to be retained but may slightly reduce variation in those variables.

## Conclusion

This project demonstrates how multiple linear regression can be used not only for prediction, but also for statistical interpretation and inference. The analysis highlights the importance of combining coefficient interpretation, confidence intervals, standardized effects, diagnostic checking, and discussion of limitations when drawing conclusions from data.

## Tools Used

- Python
- pandas
- NumPy
- matplotlib
- seaborn
- statsmodels
- scikit-learn
- Jupyter Notebook