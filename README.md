# Harvest Market Price Check

A public page comparing Harvest Market's retail prices with Walmart, Stop & Shop, Big Y, Whole Foods and Amazon.

**Live page:** https://itsmoshahrukh.github.io/harvest-price-check/

## Files

| File | What it is |
|---|---|
| `index.html` | The web page. You don't need to edit this. |
| `prices.csv` | The price list the page reads. This is the only file that changes. |

## How prices are updated

- The top 50 sellers are checked every week.
- All other retail items are checked on a rotating schedule, oldest first, so each item gets a fresh price about once a month.
- Prices come from free web searches of store websites for the Amherst, MA area.

To publish new prices, upload the new `prices.csv` (Add file > Upload files) and commit. The page updates within a minute or two.

## Notes

- "Our price" is the average selling price at the Harvest Market registers.
- Competitor prices are for the same item and size where one could be found. A dash means not found yet, or the store doesn't carry it.
- No sales figures are stored in this repository.
