# Duka Electronics Sales Exploration

## Project Summary

This project explores Duka Electronics sales data for the January–June 2026 half-year review. The dataset contains 1,000 orders across five branches and is analysed using pandas and NumPy. The analysis focuses on branch performance, product performance, weekday versus weekend sales, monthly revenue trends, and Premium Online orders from Nairobi and Mombasa.

An Excel workbook is also included to reproduce the branch revenue analysis using SUMIFS, add branch regions using XLOOKUP, and summarise revenue by branch and channel using a PivotTable.

## Questions Answered

1. Which branches generated the highest total revenue and number of orders?
2. Which three products generated the highest revenue and sold the most units?
3. How do weekend and weekday orders compare in order count, total revenue, and average order revenue?
4. Which month generated the highest revenue and which generated the lowest revenue?
5. How many Premium Online orders came from Nairobi and Mombasa, and how much revenue did they generate?

## Executive Summary

- Nairobi was the top-performing branch, generating KES 26,106,100 from 376 orders.
- Laptops generated the highest product revenue at KES 41,535,000, while Tablets led unit sales with 691 units.
- Weekdays generated KES 51,856,200 from 723 orders, while weekends generated KES 19,936,300 from 277 orders and had a slightly higher average order revenue of KES 71,972.20.
- April was the strongest revenue month at KES 13,518,300, which was 23.98% higher than June, the weakest month at KES 10,903,400.
- The Premium Online segment from Nairobi and Mombasa contained 83 orders and generated KES 10,218,000 in total revenue.

## Project Files

- `generate_data.py` — generates the 1,000-order Duka Electronics dataset using seed 2026.
- `duka_sales.csv` — generated sales dataset.
- `duka_sales_exploration.ipynb` — pandas and NumPy sales analysis.
- `outputs/premium_online_coast_capital.csv` — filtered Premium Online orders from Nairobi and Mombasa.
- `excel/duka_branch_summary.xlsx` — Excel analysis containing SUMIFS, XLOOKUP, and a revenue PivotTable.
- `requirements.txt` — Python libraries required to run the analysis.

## How to Regenerate the Data

Install the required libraries:

```bash
pip install -r requirements.txt
```
