# 06 - 	Data Cleaning

## Dataset

### Shopify Orders Dataset

- Source: Kaggle
- Original Dataset: https://www.kaggle.com/datasets/mabdullahkhalil/shpify-orders-dataset
- License: Check the Kaggle dataset license before redistribution.

## Task 1 – Data Quality Assessment

**Business Question**  
Before analyzing sales, what data quality issues exist in the dataset?

**Answer**  
![data_quality_assessment](Screenshots/task_1.png)

**Reflection**  
Auditing the dataset upfront revealed the scope of issues — duplicates, blanks, mixed formats. I learned that analysts must first measure quality before fixing it, ensuring cleaning is systematic not random.

## Task 2 – Standardize Country Names

**Business Question**  
Can we accurately analyze sales by country?

**Answer**  
![standarized_country_names](Screenshots/task_2.png)

*Yes ,* we can analyze sales by country accurately now.

**Reflection**  
Aligning country names taught me that inconsistent text can fragment geographic analysis. Standardization ensures reliable market insights.

## Task 3 – Evaluate Missing States

**Business Question**  
Are blank State values actually missing data?

**Answer**  
![evaluate_missing_states](Screenshots/task_3.png)

*No ,* they are not missing data. As only US states are mentioned only because each one has different law.

**Reflection**  
Distinguishing between expected blanks (international orders) and missing data (US orders) showed me that cleaning requires judgment, not just formulas.

## Task 4 – Standardize Order Dates

**Business Question**  
Can all orders be analyzed chronologically?

**Answer**  
![standarize_order_dates](Screenshots/task_4.png)

*No ,* they cannot be analyzed chronologically because we have to convert them in a standard format as now converted.

**Reflection**  
I standardized all order dates into a consistent format so that Excel recognizes every value as a valid date. This enables accurate time-based analysis, such as monthly sales trends, seasonal reporting, and year-over-year comparisons.

## Task 5 – Missing Customer Emails

**Business Question**  
Which orders cannot be used for email marketing?

**Answer**  
![missing_customer_emails](Screenshots/task_5(a).png)
![missing_customer_emails](Screenshots/task_5(b).png)

*121 orders* with no Email addresses about 6% of total orders cannot be used for email marketing.

**Reflection**  
Identifying missing emails highlighted how CRM and marketing depend on complete customer records. Analysts must flag gaps that weaken engagement strategies.