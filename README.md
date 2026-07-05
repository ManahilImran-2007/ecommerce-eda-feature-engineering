# E-commerce EDA & Feature Engineering

Project 1 of a data science internship — advanced exploratory data analysis 
and feature engineering on a 1200-row e-commerce order dataset.

## What I did
- Handled missing values in `CouponCode` (309 rows) by identifying that 
  the missingness was meaningful (no coupon used), not random — filled 
  with a `NoCoupon` label instead of a statistical imputation.
- Detected and treated outliers in `TotalPrice` using the IQR method, 
  capping (winsorizing) 8 legitimate high-value orders rather than 
  deleting them.
- Engineered 3 new features: `OrderMonth`, `HasDiscount`, and 
  `CartConversionRate`.

## Tools
Python, Pandas, Google Colab

## Files
- `Project1.ipynb` — full code and analysis
- `cleaned_data.xlsx` — final cleaned dataset

**Author:** Manahil Imran
