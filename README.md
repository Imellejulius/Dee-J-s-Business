# Dee & J's Business V2.2

A no-paid-dependency, local-first responsive web app for Dee & J's Consumer Goods Trading.

## Included
- Responsive phone/tablet/desktop layout with no two-column overlap on narrow phones
- Orders, procurement/cash control, products, workers, expenses
- Auto Pricing: target profit + COGS + delivery expenses -> required sales, markup and suggested item prices
- Reports & Trends: product profit bars, margin bars, order-profit trend
- Vehicle Acquisition Cost (replaces Tamaraw affordability calculator)
- A4 Sales Invoice builder + Print / Save PDF
- A4 Receiving Goods report + Print / Save PDF
- Settings, JSON backup, PWA manifest, offline cache

## Free ways to run it
### 1. GitHub Pages (recommended free host)
Create a free GitHub account/repository, upload all files in this folder to the repository root, then enable **Settings > Pages > Deploy from a branch > main / root**. GitHub gives you an HTTPS URL. No Netlify credits are required.

### 2. Local/offline
Any simple local web server can serve this folder. The app has no paid APIs or package dependencies.

## Data
V2.2 is local-first and stores data in the browser's localStorage. Different phones do NOT sync yet. Export JSON backups from Settings. Clearing browser/site data can erase local records.

## Continue with another AI / developer
Give them this entire folder and `PROJECT_SPEC.md`. Everything is plain HTML/CSS/JavaScript; there is no build step, framework, API key, or paid dependency.
