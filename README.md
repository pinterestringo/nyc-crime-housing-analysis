# NYC Crime & Affordable Housing Analysis 

**Course:** Introduction to Python | CUNY Baruch College  
**Team:** Anna Treyger, Hana Dauti, Tracy Zheng, Nawang Lama

## Overview
A data analysis project exploring the relationship between affordable housing 
concentrations and crime rates across 10 Brooklyn neighborhoods during the 
2023 holiday season (December 17–31). Uses NYC open data to investigate 
whether low-income housing density correlates with higher arrest rates.

## Key Findings
- Strong positive correlation (0.79) between low-income housing units and arrest counts
- East New York (zip 11208) had the highest arrests (199) in the observed period
- Contrary to expectations, crime was **lowest** on Christmas and New Year's Eve —
  likely due to family gatherings and increased security, consistent with 
  Routine Activity Theory
- Middle-income housing showed a weak negative correlation (-0.26) with arrests

## Methods & Tools
- **Data sources:** NYC Arrests Dataset, NYC Affordable Housing Dataset (open data)
- **Data cleaning:** dropped duplicates, handled missing values, renamed columns, 
  converted dates to datetime, calculated resolution time, validated zip codes with regex
- **Analysis:** correlation matrices, borough-level summaries, time-series by date
- **Libraries:** pandas, datetime, re

## Files
- `nyc_crime_housing_analysis.ipynb` — full Jupyter notebook with code and outputs
- `cleaning_documentation.txt` — documented data cleaning steps
- `analysis_results.txt` — summary statistics and findings
- `AnnaTreyger_HanaDauti_TracyZheng_NawangLama.docx` — full written report

## Built With
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)

## Business Implications
Findings suggest city resources should be targeted toward low-income neighborhoods 
outside of holiday seasons, when security presence is typically lower. Full policy 
recommendations in the written report.
