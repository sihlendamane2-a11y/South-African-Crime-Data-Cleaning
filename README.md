# SA Crime Data Cleaning - Python/pandas

## Overview
A data cleaning project using SAPS (South African Police Service) 
crime statistics 2024. The raw Excel data contains merged headers, 
inconsistent naming, and unnamed columns unsuitable for analysis. 
This project documents the full cleaning pipeline and produces a 
tidy dataset ready for dashboarding or modelling.

## Skills Demonstrated
- Real-world messy data handling (merged cells, unnamed columns)
- Dropping empty columns and standardising column names
- Missing value strategy and documentation
- Reproducible notebook structure with Markdown cells explaining 
  each decision

## Tools
Python 3 · pandas · matplotlib · Jupyter Notebook

## Data Source
SAPS Crime Statistics 2024 - saps.gov.za (publicly available)

## Key Finding
Eastern Cape had the highest volume of crime records in the 
dataset. A rate-based analysis would require population-adjusted 
figures for fair provincial comparison.

## Files
- crime_cleaning.ipynb - full cleaning notebook
- saps_clean.csv -cleaned output dataset
- crimes_by_province.png - bar chart of records by province

## How to Run
pip install pandas matplotlib openpyxl
Then open crime_cleaning.ipynb in Jupyter Notebook
