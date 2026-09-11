# Olist E-Commerce Data Analyst Assessment

## Project Overview
This project analyzes the Olist Brazilian E-Commerce Public Dataset to understand delivery performance, customer satisfaction, order value, and geographic differences.

## Dataset
- **Dataset:** Olist Brazilian E-Commerce Public Dataset
- **Source:** Olist / Kaggle
- **Data:** Multiple related e-commerce datasets including orders, customers, order items, products, payments, reviews, and sellers.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Google Sheets
- Google Looker Studio
- ChatGPT

## Methodology

### 1. Data Loading
The Olist datasets were loaded into Python using Pandas.

### 2. Data Cleaning
The analysis included:
- Checking for duplicate records
- Converting timestamp columns to datetime format
- Checking missing values
- Removing delivered orders with missing delivery dates from delivery-time analysis
- Checking data types
- Inspecting extreme delivery-time values

### 3. Data Processing
Calculated fields were created for:
- Delivery time in days
- Late delivery flag
- Delivery status
- Order value
- Purchase month
- Total items
- Seller count

Related datasets were joined using appropriate keys such as order ID and customer ID.

### 4. Analysis
The analysis focused on:
- Late delivery rate
- Average delivery time
- Customer review scores
- State-level delivery performance
- Seller performance
- Order value
- Monthly trends

## Key Findings

- 8.11% of delivered orders were late.
- Late orders took an average of 31.52 days compared with 10.88 days for on-time orders.
- Average review score was 2.57 for late orders compared with 4.29 for on-time orders.
- Ceará (CE) had a late delivery rate of 15.32%, while São Paulo (SP) had 5.89%.
- Some high-volume sellers had late delivery rates above 20%.

## Recommendations

1. Monitor and improve performance of high-risk sellers.
2. Prioritize logistics improvements in high-risk states such as CE, BA, RJ, and ES.
3. Introduce proactive communication for potentially delayed orders.

## Dashboard
An interactive Looker Studio dashboard was created to monitor:
- Delivered orders
- Average delivery time
- Late delivery rate
- Total order value
- Average review score
- Monthly order trends
- State-level performance

## Project Links

- **Google Sheets Assessment:** [Open Google Sheet](https://docs.google.com/spreadsheets/d/1YI-QXxgB4_NQDT2eo2cQ9sokBccl9vdFAoK5WwVjnmg/edit?gid=765953795#gid=765953795)
- **Looker Studio Dashboard:** [Open Interactive Dashboard](https://datastudio.google.com/u/0/reporting/1501d98b-f7c6-434b-afcd-44f0b673e2b9/page/jRg8F)

## Limitations

- Some delivered orders had missing delivery dates.
- Some orders did not have review scores.
- Extreme delivery-time outliers were present.
- The analysis is observational and does not establish that late delivery directly caused lower customer reviews.

## Files Included

- Google Sheets assessment workbook
- Python/Colab analysis notebook
- Looker Studio dashboard
- Dashboard PDF
- Presentation
- README / Methodology

## Conclusion

The analysis shows that delivery performance is an important operational and customer-experience factor. Targeting high-risk sellers and regions, while improving proactive customer communication, can help reduce delivery delays and improve customer satisfaction.
