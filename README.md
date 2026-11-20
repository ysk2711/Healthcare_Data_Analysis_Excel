# Healthcare Data Analysis Using Microsoft Excel

## 1. Project Overview
An exploratory healthcare data analysis project using Microsoft Excel to examine synthetic antibiotic susceptibility testing (AST) data and identify meaningful patterns.

## 2. Project Objectives
- Identify data quality issues and inconsistencies.
- Analyse antibiotic susceptibility patterns.
- Examine trends across hospital units and patient demographics.
- Develop an interactive dashboard to communicate findings.

## 3. Dataset
- 1,921 records
- 240 unique Test IDs
- 6 Pathogens
- 8 Antibiotics

## 4. Tools & Techniques
- Microsoft Excel
- Data Cleaning and Preprocessing
- Excel Functions
- Pivot Tables
- Data Visualization
- Interactive Dashboards

## 5. Data Cleaning
- Identified and handled missing values.
- Investigated duplicate records.
- Standardized inconsistent categorical entries.
- Identified potential data anomalies.

## 6. Analysis Performed
- Identified potential data anomalies.
- Dataset Enrichment: Added columns “Drug_Class” and “Gram_Type” from different reference sheets using =XLOOKUP() function.
- Data Extraction: Added a new sheet named “EDA_Formulas” which had extracted data from the cleaned dataset. Organism-wise and antibiotic-wise S/I/R distribution was calculated using =COUNTIF(), =COUNTIFS(), =AVERAGEIFS()
- Pivot Analysis: Analyzed the dataset using pivot tables. Made insightful charts for Organism-wise, Antibiotic-wise, Hospital unit-wise, Specimen type-wise susceptibility distribution percentage. Additionally, added charts for time-based analysis showing test volume yearly and quarterly.

## 7. Dashboard
![Healthcare Data Analysis Dashboard](Healthcare_Data_Analysis_Excel/Synthetic_Antibiotic_Susceptibility_Analysis_Dashboard.png)

## 8. Key Insights
- The overall resistance percentage was 45.78%.
- The organisms had 72.92% resistance against Vancomycin, which was the highest among all the antibiotics.
- Gentamicin had 38.33% resistance, which was the lowest among all the antibiotics.
- The most resistant organism was A.baumannii, with 71.43% resistance against the antibiotics.
- S.aureus showed 31.44% resistance against the antibiotics, which was the least among all the organisms.

## 9. Project Files
- Excel Workbook
- Dashboard Screenshot
- Detailed Project Report
