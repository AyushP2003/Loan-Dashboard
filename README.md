# Loan Analytics Dashboard

## Project Overview
This project delivers a visually rich loan analytics dashboard using Power BI, integrating DAX for calculations and SQL for advanced preprocessing. The loan dataset, sourced from Kaggle, covers applicant demographics, financial profiles, loan amounts, risk metrics, and performance indicators to inform better lending decisions.

## Data Source & Cleaning
- **Source:** Kaggle loan dataset [web:6].
- **Cleaning:** SQL queries handled missing data (e.g., ignored nulls in 'Arrival Delay'), removed duplicates, standardized categories, and generated age bins before import to Power BI [attached_image:1][attached_image:2][attached_image:3].

## Technology Stack
- **Power BI:** Dashboard authoring, interactive visuals, and sharing.
- **DAX:** Used for calculated columns (age groups, percentages) and measures (loan statistics, yearly trends).
- **SQL:** Data cleaning and transformation before analysis.

## Dashboard Features

### Visuals and KPIs

- **Applicant Demographics & Financial Profile:**  
  - Median loan amount by credit score: Ranges from $127,149 (high credit) to $128,397 (low credit).
  - Loan amounts visualized by education type: Most loans from Bachelor’s holders (64,366), lowest for PhDs (63,537).
  - Average loan (by age group): Highest for adults ($127,901), lowest for teens ($126,674).
  - High-credit applicants: Average loan amount for singles is $128.57 (8.43%), for married $128.35 (8.42%).
  - Loan distribution by dependents/mortgage among middle-aged adults is even ($3.1bn each).

- **Financial Risk Metrics:**  
  - YOY default change: Highest positive in 2015 (2.7), lowest in 2017 (-2.8).
  - YOY loan amount change: Highest in 2018 (1.73), negative in 2014 and 2017.
  - Largest segment for loan bin by credit: $0.67bn for medium and high scores (all marital statuses).
  - Total loan amount: $32,576,880,572 with $21.7bn attributed to high-income applicants.

- **Loan Overview:**  
  - Loan amount by purpose: Home ($6,545), Business ($6,522), Education ($6,511).
  - Average income: Full-time ($82,890), Self-employed ($82,447), Unemployed ($82,272).
  - Default rate: Highest for unemployed (3.39%), lowest for full-time (2.36%).
  - Default rate by year: Peaks in 2016 (11.75), drops in 2017 (11.50), rises again by 2018 (11.60).

## Usage and Exploration
Load the cleaned dataset into Power BI, making use of the provided DAX formulas and measures for segmentation and KPI tracking. Use dashboard filters for further insights by age group, education, credit score, purpose, or employment type.

## Conclusion
The dashboard provides rapid, visual insights for loan officers and financial analysts—helping spot risk trends, segment customers, and manage lending more effectively. SQL preprocessing ensures data accuracy, and DAX enables dynamic analysis in Power BI.

---
