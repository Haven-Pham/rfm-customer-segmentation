# Data

Synthetic e-commerce data created for analytics education: a retailer of beauty and home-care products, with
51,290 order lines from 2020 to 2023. The data do not describe a real company or real people.

## `EcomSales.csv` (one row per order line)

| Column | Description |
|---|---|
| `RowID` | Line identifier |
| `OrderID` | Order identifier (an order can have several lines) |
| `OrderDate` | Order date (M/D/YYYY) |
| `CustomerID` | Customer identifier |
| `Segment` | Consumer, Corporate or Self-Employed |
| `RegionCode` | Delivery region |
| `ProductCode` | Product identifier |
| `Quantity` | Units |
| `Sales` | Line revenue (USD) |
| `Discount` | Discount rate (0–1) |
| `Profit` | Line profit (USD); negative when the line loses money |

## Known data issues

Two product codes and one region code carry a tripled prefix (for example `PPP000002`). They do not affect this
analysis, which uses only customer, order, date and revenue fields.
