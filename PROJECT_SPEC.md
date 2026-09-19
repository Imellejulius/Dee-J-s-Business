# Dee & J's V2.3 Project Handoff

## Goal
Mobile-first hospital delivery management web app for Dee & J's Consumer Goods Trading. Must remain usable on iPhone, Android, tablet and desktop without horizontal form overlap.

## Stack
Static HTML/CSS/vanilla JS. LocalStorage persistence. PWA manifest/service worker. No build step. No paid dependency.

## Core data
`deej_v2`: orders, procurement, products, workers, expenses.
`deej_v22_settings`: business settings.
`deej_v22_invoice`: current invoice line items.
`deej_v22_receiving`: current receiving line items.
`deej_v22_vehicle`: vehicle acquisition assumptions.

## UX rules
- <=600px: forms are single-column, dashboard cards max 2 columns, fixed 5-button bottom navigation.
- Tables may scroll horizontally inside their own card; page itself must not overflow horizontally.
- A4 documents must print cleanly with controls/navigation hidden.
- Keep D&J navy/green/white branding and `app-icon.png`.

## Pricing formula
Required sales = delivery COGS + other delivery expenses + target profit.
Markup on COGS = (required sales - COGS) / COGS.
Suggested product price allocates the required-sales factor proportionally to each product's purchase cost.

## Next logical version
V2.3 Cloud Sync: use a free-tier backend only if the owner chooses it. Add authentication, shared business workspace, roles (Owner/Admin/Worker), conflict-safe CRUD, backup/import, and migration from localStorage. Keep a local/offline mode.


## V2.3 additions
- Admin dashboard sales mix pie chart and sales/profit trend chart with 30-day, 3-month and 1-year views.
- Manual / Phone Order workflow for orders received by call, text, chat or in person.
- Multi-item order entry using the Product master, quantities, units and adjustable selling price.
- Emergency-order toggle with configurable emergency markup percentage.
- Manual orders feed the existing order history, dashboard KPIs, analytics and profit calculations.
