# Festive-Season (Diwali) Retail Sales Analysis

By Shiva Lakshmi Padala

## Problem
Who spends the most during Diwali, where, and on what, so a retailer can target campaigns and plan stock?

## Dataset
Diwali Sales Data (public dataset): 11,251 customer orders, 15 columns.

## Tools
Python, pandas, Matplotlib, Plotly, Google Colab

## Approach
1. Loaded and inspected the data
2. Cleaned it: dropped empty columns, 12 rows with missing Amount and 8 duplicate rows (11,231 records remained)
3. Answered 13 business questions with charts: gender, age group, state, marital status, occupation and product category
4. Summarized findings and recommendations

## Key findings
- Women contribute about 70% of total spend (74.3M vs 31.9M for men)
- The 26-35 age group is the largest buying segment
- Uttar Pradesh, Maharashtra and Karnataka lead among states
- Food is the top product category by spend
- IT sector customers are the highest-spending occupation

## Recommendations
1. Target women aged 26-35 with festive campaigns
2. Prioritize the top states for ad budget and early stock allocation
3. Build festive bundles around Food and Clothing, and cross-sell Electronics and Footwear
4. Test separate offers for lower-spend segments

## Limitations
Descriptive analysis of a single festive season, so it shows what happened, not why.

## How to run
1. Download `Diwali Sales Data.csv` from a public source (for example Kaggle)
2. Open `Diwali_Sales_Analysis_v2.ipynb` in Google Colab and upload the CSV
3. Run all cells
