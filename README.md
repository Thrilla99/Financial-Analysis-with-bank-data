# Financial-Analysis-with-bank-data
Preforming analysis with simulated banking data, sourced from Kaggle  (https://www.kaggle.com/datasets/computingvictor/transactions-fraud-datasets/code)


Banking Customer and Credit Risk Analysis (Power BI Project)
Overview

This project analyzes customer, transaction, and card data from a simulated financial institution.
The goal was to uncover trends in spending, refund behavior, and credit risk across different customer and card segments.
Using Power BI, I built a data model connecting multiple datasets and designed five interactive dashboards to visualize business insights clearly and effectively.

Objectives

Understand overall customer and transaction performance.

Identify spending and refund patterns by card type and credit group.

Evaluate merchant performance and transaction concentration.

Segment customers by credit score to assess credit risk exposure.

Build a data-driven foundation for improving financial decision-making.

Data Preparation

Cleaned and standardized columns (renamed headers, removed nulls, corrected data types).

Created calculated columns such as:

Month Name and Year for time analysis.

Flow Type to separate inflow and outflow transactions.

Credit Risk Group (Very Low to Very High) based on credit score ranges.

Built DAX measures for metrics including:

Total Spend

Total Refunds

Refund Rate %

Average Spend per User

High Credit Tier segmentation

Dashboards Created
1. Executive Overview

Provides a high-level summary of total transactions, users, spending volume, average spend, and credit score trends.
Includes visuals for spending by credit tier and transaction type to show overall customer and financial health.

2. User Dashboard

Explores customer demographics and behavior, including age range, gender differences, and spending distribution by credit tier and birth month.

3. Merchants Dashboard

Highlights top merchants by transaction volume and spending concentration.
Shows refund rate and merchant-level performance to identify dependency on high-volume partners.

4. Card Type and Transactions

Compares total spending and transaction volume between Credit, Debit, and Prepaid cards.
Reveals that debit cards contribute the highest total spend but also carry higher refund activity.

5. Credit Risk View

Assesses customer reliability by segmenting users into credit risk groups.
Displays total spend, refund rate, and refund volume by both credit group and card type to identify high-risk customer segments.

Key Insights

Total spend across all customers: $572M

Total refunds: $68M, representing an average refund rate of 5%

High and Very High credit score customers account for the largest share of total spend but maintain lower refund rates (around 4%).

Subprime and low-score groups have smaller spending shares but higher refund behavior, indicating elevated financial risk.

Debit card users drive the majority of spending but are also linked to the highest refund amounts.

Merchant 27092 shows the largest transaction concentration, suggesting a potential reliance risk on specific merchants.

Business Recommendations

Maintain focus on medium- and high-credit customers who deliver consistent spending with low refund rates.

Implement stronger refund policies and monitoring for debit card users and low-credit groups.

Diversify merchant partnerships to reduce overexposure to a small number of high-volume accounts.

Develop retention programs for reliable customers with high spend and strong credit histories.

Tools and Skills

Power BI for dashboard design and data modeling.

Power Query for data transformation and cleaning.

DAX for calculated columns and key performance measures.

Data Analytics Concepts: financial segmentation, credit risk scoring, and refund analysis.
