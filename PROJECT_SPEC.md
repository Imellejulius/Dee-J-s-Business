# Dee & J's Business — V2.4 Admin Workflow

Core workflow: Order -> Additional Orders -> Item Master -> Purchase List -> Procurement -> Delivery -> Profit -> Reports.

## Order behavior
A manual/phone order can create a new order or attach item lines to an existing order. Attached lines are marked as additional and can carry remarks. Totals are rolled into the existing order.

## Item Master
Stores reusable product name, unit, selling price and current purchase cost. Market cost can be updated as prices change.

## Purchase List
Select an order to generate an A4 market buying list containing item, quantity and unit. Buyer-facing blanks are included for market price, actual quantity and notes. Internal markup is not printed.

## Storage
Static HTML/CSS/JS, localStorage, GitHub Pages compatible. Shared multi-device sync is intentionally deferred.
