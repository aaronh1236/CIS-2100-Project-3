# Market Basket Analysis

## Objective
Identify the top 10 frequent itemsets for each store and across the organization. These insights aim to:
- Understand customer shopping patterns.
- Optimize inventory management.
- Enhance marketing strategies.

## Methodology
- **Data Source**: Transaction data from 20 stores.
- **Algorithm Used**: Apriori Algorithm.
- **Metric**: **Support**  
  Support measures how frequently an itemset appears in transactions:  
  \[
  \text{Support(A)} = \frac{\text{Count of transactions containing A}}{\text{Total number of transactions}}
  \]

  **Example**:  
  If 30 out of 100 transactions include both *Activity Monitor* and *Smart Scale*, the support for the itemset `{Activity Monitor, Smart Scale}` is:  
  \[
  30 / 100 = 0.30
  \]

- **Significance of Support**:  
  - Filters out less frequent itemsets.
  - Focuses analysis on itemsets with significant customer interest.

## Key Insights
1. **Frequent Itemsets**:  
   - Top-performing products include *Activity Monitor*, *Smart Scale*, and *Fitness Tracker*.  
   - High support values across multiple stores indicate strong customer preference for these products.

2. **Applications**:  
   - **Marketing**: Design targeted promotions for frequently bought itemsets.  
   - **Inventory Management**: Optimize stock levels to match customer demand.  
   - **Customer Experience**: Align product offerings with preferences to boost satisfaction.

## Conclusion
Understanding frequent itemsets enables the fitness corporation to refine strategies for better customer engagement and operational efficiency. This data-driven approach ensures alignment with customer needs and maximizes business performance.
