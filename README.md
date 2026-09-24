## Inventory Data: Jake Cross

**Inventory.csv**
Original transaction-level dataset converted from the Excel inventory report. Contains sales dates, customer IDs, products, quantities, net revenue, order sources, and wine club names.

**Inventory_Cleaned.csv**
Cleaned transaction-level data with 38,597 rows and 27 columns. Removed one blank row, standardized text and dates, created club groupings and time variables, and flagged 14 negative-quantity transactions as returns/adjustments without deleting them.

**Inventory_Monthly.csv**
Monthly time-series dataset covering October 2025 through July 2026. Contains monthly quantities, revenue, unique orders, unique customers, transaction counts, adjustments, and per-order averages. October is a partial month.

**Inventory_Monthly_by_Source.csv**
Monthly sales broken down by Point of Sale, Wine Club, Admin Cart, and Web Store. Contains 31 month-by-source observations, including quantity, revenue, and unique order counts.

**Jake_Cross_Inventory_Cleaning.ipynb**
Python notebook documenting the data cleaning, validation, club categorization, and time-series preparation.

**Note:** These files contain sales transactions, not membership-status histories. Identifying true cancellations versus club switches requires the membership datasets.
