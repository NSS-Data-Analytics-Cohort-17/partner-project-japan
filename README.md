## Project Overview

This project analyzes BDI-3 assessments used by the Tennessee Early Intervention System across five developmental domains and 13 subdomains. The analysis addresses duplicate records, repeated assessments, missing identifiers, and malformed values.

#### [PRIVACY NOTICE]
The source data is excluded from this repository to protect the privacy and confidentiality of the children’s records. The repository contains analysis code only.

## Project Objective

Identify high- and low-performing developmental areas, evaluate score consistency across domains and age groups, and determine whether a proposed total-score criterion would identify children not eligible under existing domain-based rules.

## Technologies Used
- Python
- Jupyter Notebook

## Techniques and Methodology Used
- Data cleaning and per-child aggregation with pandas
- Numerical and correlation analysis with NumPy
- Quantile segmentation using quartiles and tertiles to compare scoring cohorts
- Age segmentation into newborn, infant, and toddler groups
- Domain and subdomain comparative analysis
- Rule-based eligibility scenario modeling
- Statistical visualization with Seaborn and Matplotlib