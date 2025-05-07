# Renewable Energy and Heating Demand in the U.S.  
**Project: Udacity Advanced Data Wrangling**

This project investigates U.S. renewable energy consumption and production in relation to heating demand, measured via Heating Degree Days (HDDs). Originally aimed at finding direct correlations between HDDs and renewable energy use, the study evolved into a broader modeling and clustering analysis of state-level production-consumption dynamics. It was completed for the final project in Udacity’s Advanced Data Wrangling course.

---

## Goals

- Gather real-world data using multiple methods (API + bulk file download)
- Assess and clean data programmatically and visually
- Build and store cleaned datasets following reproducible data practices
- Apply linear regression and clustering to model production-consumption patterns
- Evaluate whether renewable energy resilience varies across states

---

## Data Sources

- **Renewable Energy Data:** Retrieved via API from the U.S. Energy Information Administration (EIA), filtered for total renewable production (REPRB) and consumption (RETCB).
- **Heating Degree Days (HDDs):** Bulk downloaded from EIA SEDS repository; selected for consistent and long-term coverage from 1960 to 2023.

---

## Key Methods

- Data wrangling using Python (Pandas, NumPy, regular expressions)
- Visual and programmatic data assessment for quality and structure issues
- Cleaning, transformation, and merging of disparate data formats
- Linear regression with one-hot encoded categorical features (state-level coefficients)
- Unsupervised clustering based on production-consumption slope groupings
- Visualizations using Matplotlib and Seaborn

---

## Results

- **No strong national correlation** found between HDDs and renewable energy consumption
- Linear regression models revealed **state-level variation** in production-consumption relationships
- Clustering of state slopes uncovered regions with high or low renewable energy resilience
- **Predictive model** demonstrated capability to impute consumption values for missing or anomalous records

---

## Reflection

With more time and data granularity (e.g. energy source types, intra-state breakdowns), the analysis could be extended to finer insights on policy, geography, and infrastructure impact. This project provided hands-on experience with dirty, real-world datasets and the full data pipeline from acquisition through modeling.

---

*Submitted as part of the Udacity Data Analyst Nanodegree. All code and results were evaluated against detailed rubric criteria and received top marks.*