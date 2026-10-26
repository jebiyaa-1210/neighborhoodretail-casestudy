# Data Guide

Observation logs from the neighborhood mart case study. Everything was recorded by direct observation, with no surveys and no extra work for staff. Personal details are not included, and wording has been lightly cleaned.

## daily-visit-log.csv

One row per product observed.

| Column | Meaning |
|---|---|
| item | Product name |
| quantity | Typical quantity handled (sacks, boxes, etc.). Blank if not recorded |
| repackaging_done | Whether the shop repackages the item (Yes / No) |
| repackaging_details | How the repackaging is done: batch size, staff, time taken |
| customer_moment | A customer reaction or behavior I noticed |
| struggle_or_friction | A difficulty the shop faces with this product |
| profit_level | Rough profit level: Very low / Low / Moderate / High / Very high |

## bulk-stock-orders.csv

One row per bulk order.

| Column | Meaning |
|---|---|
| item_ordered | Product ordered in bulk |
| quantity_ordered | How much is ordered at a time |
| reorder_interval | Roughly how long the stock lasts before reordering |
| supplier_source | Where the stock comes from |
| receipt_available | Whether a receipt exists for the purchase |
| receipt_notes | Details about the receipt |

Profit levels are qualitative estimates, not exact figures.
