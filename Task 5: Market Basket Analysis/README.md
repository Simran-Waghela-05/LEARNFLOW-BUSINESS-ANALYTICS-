# Task 5: Market Basket Analysis
## Problem Statement: 
Apply market basket analysis on this e-commerce dataset to discover associations between products frequently purchased together. 
Provide recommendations for marketing campaigns. 

## Project Overview
This project involves performing market basket analysis on a large e-commerce dataset. The goal is to discover associations between products frequently purchased together and provide actionable recommendations for marketing campaigns. The project uses the Apriori algorithm to identify these associations.

## Dataset
The dataset used for this analysis contains the following columns:
- **InvoiceNo:** Invoice number. A unique identifier for each transaction.
- **StockCode:** Product code. A unique identifier for each product.
- **Description:** Product description.
- **Quantity:** The quantity of each product per transaction.
- **InvoiceDate:** The date and time when a transaction was generated.
- **UnitPrice:** Unit price of each product.
- **CustomerID:** Unique identifier for each customer.
- **Country:** The country where the customer resides.

## Analysis Steps
1. **Data Preparation:**
   - Loading the dataset.
   - Converting the `InvoiceDate` column to datetime format.
   - Creating an item basket by grouping data by `InvoiceNo` and `Description`.
2. **Data Encoding:**
   - Encoding the item basket so that quantities are binary (0 or 1).
3. **Applying Apriori Algorithm:**
   - Using the Apriori algorithm to identify frequent itemsets with a minimum support of 0.01.
4. **Generating Association Rules:**
   - Generating association rules from the frequent itemsets.
   - Filtering the rules based on a lift value greater than 1.
5. **Recommendations:**
   - The resulting association rules can be used to inform marketing strategies, such as product bundling and targeted promotions.

## Result
The association rules generated from the analysis can help identify products that are frequently purchased together, enabling the creation of effective marketing strategies.

