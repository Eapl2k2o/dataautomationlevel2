Scenario A — The Loyalty Question

"The CEO wants to know before the next investor call: "Are we actually building repeat customers, or are we still chasing one-time buyers every month? Show me the trend.""

Tasks

1.	Clean the data: duplicates, nulls, and exclude Cancelled/Returned orders.
2.	Calculate NetSales per order.
3.	Roll up NetSales by month (Mon-YYYY) split by CustomerType (New vs Returning).
4.	Identify the month with the highest and the lowest share of revenue from Returning customers.
5.	Build a stacked or area chart of New vs Returning revenue over time, in chronological order.
6.	One-line verdict: is the business getting more dependent on returning customers over time?

   
Constraints

●	Months grouped by OrderDate, formatted Mon-YYYY.

●	Share % = Returning NetSales ÷ Total NetSales for that month, as a percentage.

●	Exclude any month with fewer than 5 orders (too little data to trust).

●	Chart x-axis must be chronological, not alphabetical.

●	Percentages rounded to 1 decimal place.

