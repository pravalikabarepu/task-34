# RFM Customer Segmentation

## Project Overview

This project performs **RFM (Recency, Frequency, Monetary) Customer Segmentation** using a real-world transactional e-commerce dataset.

The objective is to identify different customer groups based on their purchasing behavior and provide actionable recommendations for customer retention, reactivation, and value enhancement.

## Objectives

* Calculate Recency, Frequency, and Monetary metrics
* Score customers based on their purchasing behavior
* Segment customers into meaningful groups
* Analyze customer value and purchasing patterns
* Build an interactive dashboard
* Generate business recommendations from customer segments

## Dataset

The project uses an e-commerce transactional dataset containing customer purchase information.

Key fields include:

* Invoice/Order Number
* Invoice Date
* Customer ID
* Product Description
* Quantity
* Unit Price
* Country

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook / VS Code
* Power BI

## Methodology

### 1. Data Cleaning

The dataset was cleaned by:

* Removing missing customer IDs
* Removing cancelled or invalid transactions
* Handling duplicate records
* Checking data types
* Creating the total purchase value

### 2. RFM Analysis

Three customer-level metrics were calculated:

**Recency:** Number of days since the customer's most recent purchase.

**Frequency:** Number of purchases/orders made by the customer.

**Monetary:** Total amount spent by the customer.

### 3. RFM Scoring

Customers were assigned scores based on their Recency, Frequency, and Monetary values.

These scores were combined to understand overall customer behavior and create meaningful customer segments.

### 4. Customer Segmentation

Customers were classified into segments such as:

* Champions
* Loyal Customers
* Potential Loyalists
* At Risk Customers
* Lost Customers

These segments help businesses understand which customers should be retained, developed, or reactivated.

## Dashboard

The interactive dashboard presents:

* Total Customers
* Total Revenue
* Average Customer Value
* Customer Segment Distribution
* RFM Segment Analysis
* Customer Value Analysis
* RFM-based customer insights

The dashboard provides a one-page view of customer behavior and helps identify high-value and at-risk customers.

## Key Business Recommendations

### Champions

Provide loyalty rewards, exclusive offers, and personalized recommendations to retain high-value customers.

### Loyal Customers

Use loyalty programs, early access offers, and personalized promotions to maintain their purchasing frequency.

### At-Risk Customers

Use targeted discounts, reminders, and personalized campaigns to encourage customers to return.

### Lost Customers

Run reactivation campaigns with attractive incentives and monitor campaign effectiveness.

### Potential Loyalists

Encourage repeat purchases through product recommendations, bundles, and personalized offers.

## Key Outcomes

* Identified customer purchasing patterns using RFM analysis
* Segmented customers based on behavioral value
* Identified high-value and at-risk customer groups
* Created an interactive dashboard for business decision-making
* Developed segment-specific marketing recommendations

## Conclusion

RFM analysis provides a practical way to understand customer behavior and identify valuable customer segments. By combining analytical insights with targeted marketing strategies, businesses can improve customer retention, increase repeat purchases, and maximize customer lifetime value.
