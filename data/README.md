# Analytical Dataset

This folder contains the analytical dataset used for the Olist E-Commerce Sales & Delivery Analysis project.

## Dataset

**File:** `olist_analysis_data.csv`

The dataset was created by combining and transforming data from four original Olist tables using SQL:

- `customers`
- `orders`
- `order_items`
- `products`

The data was joined using:

- `customer_id`
- `order_id`
- `product_id`

Additional fields were created to support delivery performance analysis:

- `delivery_days` — Number of days between the order purchase date and the actual delivery date.
- `delivery_status` — Delivery performance classification: `On-Time`, `Late`, or `Not Delivered`.

The final analytical dataset was then imported into Power BI for data modeling, KPI calculation, and dashboard development.
