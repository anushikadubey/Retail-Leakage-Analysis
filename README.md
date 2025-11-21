# Retail-Leakage-Analysis

This project analyzes revenue leakage across a retail invoice dataset spanning 2 years of a B2B online retail warehouse.
Leakage sources such as free items, cancellations, returns, and wrong pricing are identified, quantified, and visualized.
The project includes complete data cleaning, exploratory data analysis, leakage KPI generation, and a Power BI dashboard.

Data Cleaning Steps

Missing product descriptions were imputed using modal description based on stockcode.

Zero-priced and zero-quantity items were not removed; instead, they were flagged for leakage classification.

Duplicate entries and invalid invoice formats were cleaned.

total_price, leak_amount, and indicator columns were engineered.

Timestamps were standardized and day-of-week extracted.

Outlier prices and unreasonable quantities were reviewed and categorized under leakage types.

