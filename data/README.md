# Data

The data comes from a real client and is **not included** in this repository.

All customer data was pseudonymised before analysis: each customer is an ID (`M-0001`, …) and no names, emails or contact details were kept.

| File the notebook expects | Contents |
| --- | --- |
| `transactions_anon.csv` | One row per booking or payment, 1 Jan – 28 Apr 2026. Columns: `date` (dd/mm/yyyy), `time`, `member_id`, `sold_by_staff`, `service`, `plan`, `method`, `amount_gbp`, `failed_amount_gbp`, `fee_gbp`, `net_gbp`, `status` (PAID / FAILED / REFUNDED / PENDING_INTENT) |
| `cafe_product_totals.csv` | Café till product report: `Name`, `Qty`, `Value` |

To run the notebook with your own data, place files with the same structure here.
