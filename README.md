# [Python] E-Wallet-Payment-Transaction-Analysis
## I. Introduction
### 1. About the Analysis
### Why Payment & Transaction Analysis?
- Analyzing payment and transaction data helps identify:
  - **Transaction Trends:** Understanding customer payment behaviors and frequency.
  - **Anomalies & Fraud Detection:** Identifying irregularities that may indicate fraud.
  - **Product & Team Performance:** Evaluating top-performing products and teams with the lowest contributions.
- Insights from these analyses help improve financial decision-making, optimize product offerings, and enhance customer experience.
### How?
- Exploratory Data Analysis (EDA) is performed to clean and preprocess data.
- Data wrangling is applied to merge datasets, extract meaningful insights, and define transaction types.
- Business-specific rules are used to classify transactions and identify key trends.

### 2. Business Questions
- What are the trends in e-wallet payments and transactions?

- Are there any missing, duplicate, or incorrect data points?

- Which product IDs have the highest transaction volume?

- Are there any abnormal product-team assignments?

- Which team has the lowest performance since Q2 2023?

- What is the highest contributing source_id for refund transactions?

- How can transactions be categorized based on predefined rules?

- What are the statistics for each transaction type?


## II. Insights
- **High-Performing Products:** The top 3 products with the highest transaction volumes drive most of the revenue.

- **Abnormal Product-Team Assignments:** Certain products are assigned to multiple teams, which may indicate data inconsistencies.

- **Underperforming Teams:** A specific team has had the lowest transaction volume since Q2 2023, and a particular category contributes the least to its revenue.

- **Refund Trends:** A single source_id significantly contributes to refund transactions, highlighting potential customer dissatisfaction.

- **Transaction Classification:**
  - Bank transfers, withdrawals, and top-ups follow a defined pattern based on transaction type and merchant ID.
  - A segment of transactions is marked as invalid due to missing required conditions.
  - The most frequent transaction type is payment transactions.

## III. Recommendations
  - **Enhance Data Quality & Consistency:**
    - Standardize product-team assignments to ensure data accuracy.
    - Identify and correct missing or incorrect transaction records.
    
  - **Improve Product Performance:**
    - Investigate why some product categories contribute less and optimize offerings.
    - Develop marketing strategies to promote underperforming products.
    
  - **Fraud Detection & Prevention:**
    - Monitor abnormal refund transactions and implement stricter validation.
    - Identify suspicious transaction patterns for fraud prevention.
    
  - **Optimize Transaction Processing:**
    - Offer incentives for preferred payment methods to enhance customer retention.
    - Streamline transaction workflows to improve processing time.
