# Tanveer-association-mini
# Association Rule Mining with Simulated Data

This project demonstrates association rule mining using the Apriori algorithm on simulated shopping transaction data.

## Generated Rules

Based on the analysis, here are the discovered association rules:

1. **Rule**: If someone buys ['Cheese'], they are also likely to buy ['Bread']
   - **Confidence**: 0.75 (75% of cheese purchases include bread)
   - **Support**: 0.3 (appears in 30% of all transactions)
   - **Lift**: 1.25 (indicates a positive correlation)

2. **Rule**: If someone buys ['Yogurt'], they are also likely to buy ['Milk']
   - **Confidence**: 1.0 (100% of yogurt purchases include milk)
   - **Support**: 0.3 (appears in 30% of all transactions)
   - **Lift**: 1.67 (strong positive correlation)

## Real-life Interpretation

The second rule shows that customers who buy yogurt always buy milk in the same transaction. This makes practical sense because:
- Yogurt is a dairy product often consumed with milk
- Customers might be doing their weekly dairy shopping
- There might be a promotion bundling these items together

This insight could be used for:
- Product placement (placing yogurt near milk)
- Creating bundle promotions
- Inventory management (stocking more milk when yogurt is on sale)