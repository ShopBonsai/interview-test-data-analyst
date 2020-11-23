Welcome to the Bonsai Data Analyst Test! The goal is to get a sense of your work-prioritization, how you work, and the quality of the final product!

### The Task

The datasets are simplified/redacted versions of data at Bonsai. Analyze the data and present your results to senior management:
1. Summarizes sales and operations - think about which statistics, metrics, or figures are important to our business
2. Propose 2-3 areas where the company can improve
3. Any other analysis you find crucial to include and highlight cretain business KPIs

### The Data

1. Product dataset
2. Customer dataset
3. Order dataset
4. Order-item dataset: data about the products purchased within which order. As an example, order_id `00143d0f86d6fbd9f9b38ab440ac16f5`.
It has 3 items (the same product). Each item has the shipping cost listed. To get the order's total cost you sum:

```
63.99 Total raw item price for the order (21.33 * 3)
45.30 Total shipping (15.10 * 3)
----
109.29 Total order value
```

- It is up to you to decide how to combine these datasets
- Assume all orders are delivered (no refunds, no exchanges, no partial-orders)

### Some Tips

This is an open ended problem. You can select what direction the analysis takes - but keep in mind that it is a presentation to senior management. Keep your final results brief (it should take ~15 min to present).

In addition to communication, your analytical skills are evaluated. Please provide all code, documentation, and an overview of the thought process in your submission.

You are free to choose your platform for analysis and presentation. Good luck!
