# Online Sales Coupon Analysis in Python

## Overview
This project analyzes online sales data to understand coupon usage, customer engagement, and discount effectiveness. The goal is to gain insights into how coupons impact sales and customer behavior.

## Dataset Description
The project uses the following datasets:

- **train.csv**: Main data containing customer, campaign, coupon, and redemption status.
- **customer_transaction_data.csv**: Transaction details including item, price, and discounts.
- **customer_demographics.csv**: Customer details such as age, marital status, and income.
- **coupon_item_mapping.csv**: Mapping of coupons to specific items.
- **campaign_data.csv**: Campaign details (type, start & end dates).
- **item_data.csv**: Item details including brand and category.

## Analysis Steps

### 1. Data Preprocessing
- Data Cleaning and Handling Missing Values
- Merging relevant datasets

### 2. Exploratory Data Analysis (EDA)
- Customer Engagement Analysis
- Coupon Usage Analysis
- Classification of Coupons by Product Type
- Feature Engineering (Calculating total discount, final price, and estimated profit)

### 3. Visualizations
- Category-wise sales distribution
- Coupon usage across different product types
- Discount impact on final price and profit

## Results
- Identified key product categories with the highest coupon usage.
- Analyzed customer engagement based on transaction data.
- Computed estimated profit to measure coupon effectiveness.

## Requirements
To run this project, install the following dependencies:

```bash
pip install pandas numpy matplotlib seaborn
```

## Running the Analysis
Run the Jupyter Notebook containing the analysis using:

```bash
jupyter notebook analysis.ipynb
```

## Author
Nabadeep Brahma

## License
This project is open-source and available under the MIT License.
