<img width="1842" height="655" alt="image" src="https://github.com/user-attachments/assets/5cc5e8a3-f76e-43a3-9da2-4513f9c1dfc3" />


# Bank Loan Portfolio Dashboard

An interactive Excel dashboard built on 38,500+ bank loan records, using PivotTables, PivotCharts, and connected Slicers to analyze loan performance and risk across borrower segments.

## What it does
- Tracks **loan status** (Fully Paid / Current / Charged Off) and computes a derived **Good vs. Bad Loan** classification for every record
- Analyzes **interest rate** and **DTI (debt-to-income)** trends across loan grades (A–G)
- Breaks down loan volume and quality by **purpose, home ownership, term, verification status, and state**
- Visualizes **monthly loan volume trends** across 2021
- All 6+ charts are cross-filterable via 4 connected slicers (grade, state, term, verification status), so any filter updates every chart simultaneously

## Key insights
- ~86% of loans are classified as "good" (Fully Paid/Current)
- Interest rate and DTI both increase steadily from Grade A (7.4%) to Grade G (21.4%), confirming risk-based pricing is well-calibrated
- 81% of borrowers carry a DTI under 20%, indicating a broadly healthy borrower base
- Loan issuance volume trends upward month-over-month across 2021

## Tools used
Excel PivotTables, PivotCharts, Slicers, formula-driven KPI summaries (SUMIFS/COUNTIFS/AVERAGEIFS)
