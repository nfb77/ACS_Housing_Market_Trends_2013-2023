# README

## Overview
This repository contains R code used to replicate analyses examining housing market dynamics across major U.S. metropolitan areas. The analysis draws on American Community Survey (ACS) microdata and focuses on the top 35 Metropolitan Statistical Areas (MSAs) for which consistent data were available (21 of the intended 35 MSAs).

---
## File Information
- **Data file names:** `df_indexed_rent.csv`,`growth_df_adj.csv`,`master_df.csv`,`vacancy_growth_df.csv`,`pop_growth.csv`
- **Rmd file name:** `Rethinking the Housing Crisis.rmd` 
- **Coverage:** 21 of top 35 MSA's in the U.S. (by population in 2023)
- **Time span:** 2013 – 2023  
- **Unit of observation:** MSA by year

---
## Data Sources
The analysis uses ACS 5-year estimates accessed via IPUMS or the Census API. Variables are aggregated to the MSA level and harmonized across years.

### Main Variables
The key variables used in the replication include:

| Variable        | Description                                                                 |
|-----------------|-----------------------------------------------------------------------------|
| `rent_cumulative_pct`      | Percent cumulative change in median gross rent over the study period for each MSA.|
| `pop_growth_pct`      |  (Demand) Percent change in total population over the study period for each MSA.|
| `units_pct_increase`      | (Supply)Percent increase in total housing units (or unit density) across the study period for each MSA.       |
---

