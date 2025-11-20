# README

## Overview
This repository contains R code used to replicate analyses examining housing market dynamics across major U.S. metropolitan areas. The analysis draws on American Community Survey (ACS) microdata and focuses on the top 35 Metropolitan Statistical Areas (MSAs) for which consistent data were available (21 of the intended 35 MSAs).

The replication code produces descriptive statistics, visualizations, and model estimates related to cumulative rent changes, population shifts, and housing supply responses.

---

## Data Sources
The analysis uses ACS 5-year estimates accessed via IPUMS or the Census API. Variables are aggregated to the MSA level and harmonized across years.

### Main Variables
The key variables used in the replication include:

- **`rent_cumulative_pct`**  
  Percent cumulative change in median gross rent over the study period for each MSA.

- **`pop_growth_pct`**  
  Percent change in total population over the study period for each MSA.

- **`units_pct_increase`**  
  Percent increase in total housing units (or unit density) across the study period for each MSA.

These variables are merged into a unified dataset that serves as the foundation for the analyses.

---

## Repository Structure
A suggested project structure (modify as needed):

