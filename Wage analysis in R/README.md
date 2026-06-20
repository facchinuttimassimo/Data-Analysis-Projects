# Data Analysis on Wage Dataset

This project analyzes wage determinants using the **CPS1985** dataset from the `AER` package in R. The dataset contains information on wages, education, experience, gender, union membership, and ethnicity collected in 1985 as part of the Current Population Survey.

The analysis combines exploratory data analysis with regression modeling, following a Mincer earnings equation approach.

## Methodology

- **Exploratory Data Analysis** — distribution analysis, scatterplots, and trellis plots to explore relationships between wages and key predictors
- **Log-linear Regression** — three progressively richer OLS models estimated on log-transformed wages
- **Model Selection** — formal comparison via AIC and BIC - **Residual Diagnostics** — linearity, normality, homoscedasticity, and influential observations

## Key Findings

- Each additional year of education increases wages by approximately 9%
- The gender wage gap is dynamic: it widens as experience accumulates
- Union membership carries a wage premium of about 20%
- Experience has a concave effect on wages, consistent with the Mincer model

## Dataset

- **Source**: `AER` package in R (`CPS1985`)
- **Observations**: 534
- **Period**: 1985, Current Population Survey (USA)
