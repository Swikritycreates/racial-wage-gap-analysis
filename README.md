# Wage Disparities Across Race and Region in the U.S.

This project analyzes wage differences between Black and non-Black male workers across U.S. regions using regression modeling in R. The goal is to quantify the racial wage gap while controlling for education and experience, and to test whether this gap varies geographically.

---

## Research Questions

- What is the wage gap between Black and non-Black male workers across U.S. regions?
- Does the magnitude of this wage gap differ significantly across regions?

---

## Data Source

- **Dataset:** Current Population Survey (CPS), 1988  
- **Source:** U.S. Census Bureau (via Sleuth2 R package)  
- **Variables used:**
  - Wage (weekly earnings)
  - Race (Black / non-Black)
  - Region (MW, NE, S, W)
  - Education (years)
  - Experience (years)

---

## Methods

This analysis was conducted in R using:

- Data cleaning and filtering
- Exploratory data visualization
- Linear regression modeling
- Log-transformation of wages to meet model assumptions
- Interaction modeling to test regional differences
- Partial F-test for model comparison

---

## Key Findings

- Non-Black workers earn approximately **21%–27% more** than Black workers, controlling for education, experience, and region.
- The wage gap is **consistent across regions**.
- No statistically significant evidence was found that the magnitude of the wage gap differs by region (p = 0.234).

---

## Key Visualizations

- Wage distributions by race and region (boxplots)
- Model-based predicted wage comparisons
- Regression coefficient plots with confidence intervals

---

## Tools Used

- R
- tidyverse
- ggplot2
- broom
- performance
- equatiomatic
- Sleuth2

---

## Key Insight

The results suggest that racial wage disparities persist consistently across geographic regions in the United States, even after controlling for education and experience.


[View Analysis](https://swikritycreates.github.io/racial-wage-gap-analysis/)
