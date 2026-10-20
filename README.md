# Customer Churn Analysis

## Project Overview

This project analyzes customer churn using a sample dataset to identify patterns associated with customer retention and churn. The analysis uses Excel/Google Sheets for data cleaning, exploratory analysis, churn-rate comparisons, and dashboard reporting.


## Dashboard Preview

![Customer Churn Analysis Dashboard](Dashboard_Screenshot.png)


## Business Objective

Understand which customer segments show higher churn rates and identify potential areas where a business could investigate retention improvements.

## Tools Used

- Microsoft Excel / Google Sheets
- Spreadsheet formulas and data cleaning
- Pivot tables and charts
- KPI dashboard and business insights

## Dataset

The project uses a generated sample dataset containing customer attributes, subscription details, usage patterns, support interactions, satisfaction scores, and churn status.

The original dataset contained 1,825 rows. After removing 17 exact duplicate rows, 1,808 records remained for analysis.

## Data Cleaning and Preparation

- Removed exact duplicate rows.
- Standardized category capitalization and formatting.
- Cleaned monthly fee values and applied appropriate data formats.
- Reviewed missing values and unusual observations.
- Documented unresolved churn-status values and negative tenure records rather than silently changing or deleting them.

## Key Findings

- **Preliminary churn rate:** 29.74% of records with recognized Active or Churned statuses were classified as churned.
- **Contract type:** Annual contracts showed a 31.39% churn rate, compared with 30.68% for monthly and 26.95% for quarterly contracts.
- **Subscription plan:** Premium showed a 32.18% churn rate, Basic 28.38%, and Standard 30.38%.
- **Customer satisfaction:** The low-satisfaction group showed a higher churn rate than the moderate- and high-satisfaction groups.
- **Complaints:** Churn rates were higher among records with four or more complaints, but these groups contained very few records.
- **Usage:** Splitting records around median usage showed only a small difference in churn rates.

These findings are descriptive associations, not proof of causation. Small groups should be interpreted cautiously.

## Data Quality Limitations

- Twenty-nine records have unresolved `Yes` or `No` churn-status values. These were excluded from the preliminary churn-rate calculations.
- Two records have negative tenure values and require source validation.
- Some fields contain missing values or unusual observations.
- Churn rates are record-based; unique-customer rates have not been independently verified.

## Business Recommendations

1. Investigate why annual-contract customers show a higher observed churn rate than quarterly-contract customers.
2. Review customer feedback and satisfaction patterns to identify potential retention opportunities.
3. Investigate customers with repeated complaints, while considering the small sample sizes.
4. Validate unresolved churn statuses and unusual tenure values before using the results for operational decisions.
5. Track churn by customer segment over time to identify whether patterns persist.

## Project Files

- `Customer_Churn_Analysis.xlsx` — Workbook containing data preparation, analysis, and dashboard.
- `Dashboard_Screenshot.png` — Dashboard preview.

## Disclaimer

This is a portfolio project using generated sample data for educational and analytical practice. The findings should not be interpreted as results from a real company or customer population.
