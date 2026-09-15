# SalesFlow Summary Report

## Data Quality

- Total rows processed: **6000**
- Valid rows: **5781** (96.4%)
- Quarantined rows: **219**

### Validation errors by reason

| Reason | Count |
| --- | --- |
| region: Value error, unknown region '', expected one of ['Central', 'East', 'North', 'South', 'West'] | 42 |
| order_id: duplicate | 41 |
| unit_price: Input should be greater than 0 | 36 |
| category: Value error, unknown category 'Unknown', expected one of ['Apparel', 'Beauty', 'Books', 'Electronics', 'Home & Kitchen', 'Sports & Outdoors', 'Toys'] | 36 |
| quantity: Input should be greater than 0 | 33 |
| customer_id: Value error, must not be blank | 31 |

## Business Metrics

- Total net revenue: **$6,954,414.88**
- Total orders: **5,781**
- Average order value: **$1,202.98**
- Top category: **Home & Kitchen** ($1,072,591.36)
- Top region: **North** ($1,420,546.37)

## Top 10 Products

| Product | Units Sold | Net Revenue |
| --- | --- | --- |
| 4K Monitor | 1252 | $244,135.75 |
| Rain Coat | 1245 | $232,482.14 |
| Coffee Maker | 1267 | $231,326.22 |
| Camping Tent | 1239 | $228,753.46 |
| Hair Dryer | 1092 | $221,588.63 |
| Water Bottle | 1184 | $221,488.86 |
| Cutlery Set | 1078 | $219,014.26 |
| Air Fryer | 1112 | $216,983.57 |
| Mystery Novel | 1142 | $215,413.32 |
| Puzzle 1000pc | 1048 | $211,677.00 |

## Channel Mix

| Channel | Net Revenue | Share |
| --- | --- | --- |
| In-Store | $2,333,790.98 | 33.6% |
| Online | $2,324,715.31 | 33.4% |
| Wholesale | $2,295,908.59 | 33.0% |
