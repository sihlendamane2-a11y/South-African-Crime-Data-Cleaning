
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
## Visualisation
### Crime Records by Province
<img width="1200" height="600" alt="crimes_by_province" src="https://github.com/user-attachments/assets/7b168a7f-1fdd-4019-a262-2b79a1674591" />

## Recommendations

1. Eastern Cape resource allocation: Eastern Cape had the 
   highest volume of crime records in the dataset. Government 
   should prioritise SAPS resource allocation; personnel, 
   vehicles and funding, to Eastern Cape stations 
   particularly in high-density districts.

2. Data quality improvement: The raw SAPS dataset contained 
   over 1,235 empty columns and inconsistent station naming. 
   SAPS should invest in standardised data collection systems 
   across all stations to enable faster and more reliable 
   national reporting.

3. Population-adjusted reporting: Raw record counts favour 
   larger provinces. Future SAPS publications should report 
   crime rates per 100,000 people rather than absolute counts 
   to allow fair provincial comparisons.

4. Station-level targeting: A cleaned station-level dataset 
   is now available for deeper analysis. Policymakers should 
   use station-level data to identify specific hotspot 
   stations rather than making province-wide generalisations.

## Files
- crime_cleaning.ipynb - full cleaning notebook
- saps_clean.csv -cleaned output dataset
- crimes_by_province.png - bar chart of records by province

## How to Run
pip install pandas matplotlib openpyxl
Then open crime_cleaning.ipynb in Jupyter Notebook
