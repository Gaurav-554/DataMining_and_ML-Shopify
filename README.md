<h1 align="center">Shopify Dataset - Detecting and Treating Outliers</h1>

<h2>Data Description</h2>

The dataset contains time-series sales data for a span of 30 days as explained below:

- `order_id`
- `shop_id`
- `user_id`
- `order_amount` | total amount of the order in $
- `total_items` | number of items in the given order
- `payment_method` | mode of payment (cash, debit or credit_card)
- `created_at` | timestamp associated with the given order


<h2>Objective</h2>

The objective is to see the impact of outliers on Average Order Value (AOV) and detect/remove them using inter-quartile analysis.
