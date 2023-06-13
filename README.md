# DataKind Dec 2022 DataDive

### Problem Statement:
Identifying potential eligibility-enrollment gap in localities
---

Insights from Notebook
---

Analysis

* The SNAP combined dataset shape was orginally 2536 rows and 10 columns. The SVI dataset shape was 3143 rows and 9 columns. The map meal gap 2020 dataset was 3143 rows and 24 columns. The census dataset shape was 2507 rows and 2 columns.

* There was some data loss as a result of the merge - SNAP data is missing a bit over 600 counties.

* From the histogram the household ratio 'HH_ratio' is positively skewed and normally distributed. The RPL themes bars are almost the same because they are percentile ranks.

* The scatter plot charts show SNAP benefit uptake increases with vulnerability (positive/slightly positive) except THEME3 which is the ranking for Racial and Ethnic Minority Status theme doesn't seem to be correlated.

* Correlation Coefficients: theme1 and themes (overall) has a strong positive correlation and theme4 has a slightly positive correlation.

* Correlation matrix and heatmap slightly positive relationship with HH_Ratio, Overall Food Insecurity Rate (1 Year), RPL_THEMES (SVI Overall).

