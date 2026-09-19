# Dee & J's Business V2.5 — Project Spec

## Core admin flow
Order -> Additional Order -> Purchase List -> Actual Market Purchase -> Automatic Sales Invoice -> Delivery -> Profit/Analytics.

## Item categories
Meat; Poultry; Fish & Seafood; Vegetables; Fruits; Eggs & Dairy; Groceries; Cooking Oil & Condiments; Beverages; Food Containers & Packaging; Disposable Tableware; Kitchen Supplies; Cleaning & Sanitation; Trash Bags; Tissue & Paper Products; Medical & PPE; Medical Supplies; Office Supplies; Household & Utility Supplies; Hardware & Maintenance; Other / Uncategorized.

## Purchase workflow
Purchase List is optimized for compact 80 mm printing. Each line shows item, quantity, unit and a field for actual market unit price. Additional items are tagged automatically. Finalization stores actual quantity/cost, updates latest product cost, recalculates order COGS/profit, and creates the Sales Invoice.

## Architecture
Static HTML/CSS/JavaScript, localStorage persistence, no build framework. Keep GitHub Pages compatibility and portability for future developers/AI.
