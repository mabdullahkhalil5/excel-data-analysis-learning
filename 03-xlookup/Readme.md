# 02 - 	XLOOKUP
## Dataset

### Tableau Sample Superstore Dataset

- Source: Kaggle
- Original Dataset: https://www.kaggle.com/datasets/truongdai/tableau-sample-superstore
- License: Check the Kaggle dataset license before redistribution.

## Task 1 – XLOOKUP Overview

**Business Question**  
Find the customer name for a given Order ID.

**Answer**  
![Xlookup_overview](Screenshots/task_1.png)

**Reflection**  
This task helped me to understand how to quickly retrieve customer names from Order IDs, which is essential for customer service lookups.

## Task 2 – Product Information Lookup

**Business Question**  
A salesperson enters a Product Name. Return its Category and Sub-Category.

**Answer**  
![Product_Information_Lockup](Screenshots/task_2.png)

**Reflection**  
I practiced returning multiple fields (Category, Sub-Category) at once, useful for product classification.

## Task 3 – Customer Profile

**Business Question**  
HR wants to know the customer's Segment and Region using Customer ID.

Return:

- Customer Name
- Segment
- Region

**Answer**  
![Product_Information_Lockup](Screenshots/task_3.png)

**Reflection**  
I learned how XLOOKUP can pull full customer details, strengthening segmentation analysis.

## Task 4 – Exact Match

**Business Question**  
A manager accidentally types:

*Californi*
instead of
*California*

Your formula should not return an incorrect value.

**Answer**  
![Product_Information_Lockup](Screenshots/task_4.png)

**Reflection**  
I understood the importance of exact matches to avoid wrong results when data entry errors occur.

## Task 5 – Search Order (Latest Order)

**Business Question**  
One customer has placed many orders.

Management wants to know:

*What was the customer's most recent order?*

**Answer**  
![Search_order](Screenshots/task_5.png)

**Reflection**  
I learned to search backwards to find the most recent order, key for tracking customer activity.

## Task 6 – First Order (First Order)

**Business Question**  
One customer has placed many orders.

Management wants to know:

*What was the customer's most first order?*

**Answer**  
![Search_order](Screenshots/task_6.png)

**Reflection**  
I practiced searching forward to identify first purchases, useful for onboarding analysis.

## Task 7 – Horizontal Lookup

**Business Question**  
Return Sales for all months in a row.

**Answer**  
![horizontal_lookup](Screenshots/task_7.png)

**Reflection**  
This task helped me to discover XLOOKUP that works across rows, making monthly KPI retrieval easier.