# Comprehensive-Customer-Insights-through-RFM-And-Market-Basket-Analysis

# Problem Statement
This report provides a comprehensive analysis of customer behavior using two powerful techniques: RFM (Recency, Frequency, Monetary) Analysis and Market Basket Analysis. RFM Analysis helps in segmenting customers based on their purchasing behavior, allowing businesses to identify high-value customers and tailor marketing strategies. Market Basket Analysis, on the other hand, uncovers patterns in product purchases, enabling better product placement, cross-selling, and inventory management. By integrating these two analytical approaches, businesses can gain deeper insights into customer behavior, optimize their marketing and sales strategies, and enhance customer retention and sales.

# DataSet
Source: https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset

# Market Basket Analysis
The Market Basket Analysis identifies product associations based on transactional data. The analysis highlights different levels of association strength between items, categorized into strong, moderate, and weak associations based on metrics like support, confidence, lift, leverage, and conviction.

1. Antecedents: The initial item(s) or itemset in the association rule.
2. Consequents: The item(s) that are likely to be bought together with the antecedents.
3. Antecedent Support: The proportion of transactions that include the antecedents.
4. Consequent Support: The proportion of transactions that include the consequents.
5. Support: The proportion of transactions that include both the antecedents and the consequents.
6. Confidence: The probability that the consequents are purchased when the antecedents are purchased (Support/Antecedent Support).
7. Lift: The ratio of the observed support to that expected if the antecedents and consequents were independent (Confidence/Consequent Support).
8. Leverage: The difference between the observed support and the expected support if the antecedents and consequents were independent.
9. Conviction: A measure of the implication of the antecedents on the consequents (related to the odds ratio).

# RFM Analysis:
RFM (Recency, Frequency, Monetary) analysis is a marketing technique used to quantify and segment customers based on their purchasing behavior.
1. Recency (R): How recently a customer made a purchase.
2. Frequency (F): How often a customer makes a purchase.
3. Monetary (M): How much money a customer spends on purchases.
Using RFM analysis, businesses can identify their most valuable customers, tailor marketing strategies, and improve customer retention. For instance, a dataset may include customer IDs, dates of last purchase, total number of purchases, and total amount spent, which are then used to calculate RFM scores.

By implementing these strategies based on RFM and market basket analysis insights, businesses can improve customer retention, increase sales, and optimize marketing efforts for better overall performance.

    
