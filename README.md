# Finding Patterns in Happiness - CIS 400 Project

This repository contains Learning Portfolio (LP) assignments for the project "Finding Patterns in Happiness," completed for CIS 400: Data Science in Practice at Syracuse University.

## Project Aim

To explore and understand relationships between existing well-being indicators and the overall happiness scores of countries, aiming to identify key factors influencing national and demographic well-being and provide insights relevant for policymakers.

## Repository Contents

*   **`lp-253-as02.pdf`:** Project Proposal outlining the initial aim, objectives, and data sources. 
*   **`lp-253-as03.Rmd` / `lp-253-as03.pdf`:** Assignment 03 focusing on initial data preprocessing, visualization, and database queries using the GWBI datasets. Includes R code and generated outputs/plots. *(Adapt filenames if you used plain .R scripts)*
*   **`lp-253-as04.Rmd` / `lp-253-as04.pdf`:** Assignment 04 continuing the analysis, incorporating the World Happiness Report data, performing correlations, visualizations, and building a baseline predictive (linear regression) model. Includes R code and generated outputs/plots. *(Adapt filenames if you used plain .R scripts)*
*   **`data/`:**
    *   `Global Wellbeing Initiative Dataset - Global.csv`
    *   `Global Wellbeing Initiative Dataset - Country Level.csv`
    *   `2019.csv`

## Data Sources

1.  **Global Wellbeing Initiative Dataset:** Gallup. Retrieved from [https://www.gallup.com/analytics/468179/global-wellbeing-initiative-dataset.aspx](https://www.gallup.com/analytics/468179/global-wellbeing-initiative-dataset.aspx)
2.  **World Happiness Report 2019:** Helliwell, J. F., Layard, R., & Sachs, J. D. (2019). World Happiness Report 2019. New York: Sustainable Development Solutions Network. Dataset retrieved from Kaggle: [https://www.kaggle.com/datasets/unsdsn/world-happiness](https://www.kaggle.com/datasets/unsdsn/world-happiness)

## Tools Used

*   **R Programming Language**
*   **Key R Packages:** `tidyverse` (includes `dplyr`, `ggplot2`, `readr`, `tidyr`, `stringr`), `janitor`, `corrplot`

## How to Run

1.  Ensure the required CSV data files are accessible (e.g., in a `data/` subdirectory or the main project directory).
2.  Adjust file paths within the R scripts or R Markdown (`.Rmd`) files if necessary.
3.  Run the R scripts or knit the R Markdown files (`lp-253-as03.Rmd`, `lp-253-as04.Rmd`) using RStudio or a similar R environment. The necessary packages must be installed.

## Key Findings Summary

*   GDP per capita, Social Support, Healthy Life Expectancy, and Freedom are strong positive correlates/predictors of national happiness (WHR Score).
*   Perceived and objective income levels strongly correlate with individual thriving levels globally (GWBI).
*   The GWBI Thriving Index shows a strong positive correlation (r=0.831) with the WHR Score, suggesting its utility as a well-being proxy.
