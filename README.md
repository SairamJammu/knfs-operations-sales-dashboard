# Kent Natural Food Store Operations and Sales Dashboard

Power BI business intelligence dashboard for Kent Natural Food Store (KNFS), a community co-op grocery retailer. The project turns sales, inventory, reorder, and cost data into an operational decision tool for store managers and buyers.

![Kent Natural Food Store Operations and Sales Dashboard](Screenshots/overview-dashboard.png)

## Executive Summary

KNFS needed clearer visibility into product sales, department performance, reorder risk, inventory aging, and gross margin. The final Power BI dashboard consolidates the available source data into a 10-page report with a polished executive dashboard and supporting question-level analysis pages.

The dashboard helps answer three practical management questions:

- What is selling, underperforming, and driving department revenue?
- Which inventory items need buyer attention because they are out of stock, aging, or tying up value?
- How do sales, cost of goods sold, gross margin dollars, and gross margin percentage summarize overall store performance?

## Final Deliverables

- [Power BI Dashboard](dashboard/KNFS_Dashboard.pbix)
- [Project Report](Presentation/KNFS_Report.pdf)
- [Dashboard Screenshot](Screenshots/overview-dashboard.png)

## Business Context

Kent Natural Food Store is a local grocery co-op focused on fresh produce, bulk foods, packaged goods, refrigerated products, health and beauty items, vitamins, and supplements. Because the store carries many product categories and depends on buyer-level inventory decisions, managers need quick visibility into sales performance, reorder priorities, and aging inventory.

Before this project, the available datasets were not normalized and contained inconsistent fields across sales, inventory, reorder, and cost records. This made it difficult to answer basic operating questions without manual review.

## Dashboard Scope

The final dashboard contains:

- 1 executive dashboard page
- 8 question-specific analysis pages
- 1 buyer insights page
- 13 visuals on the executive dashboard
- KPI cards for total sales, COGS, gross margin, and gross margin percentage
- Bar and column charts for product, department, reorder, and inventory analysis
- Slicers for focused inventory views

## Data Model and Preparation

The Power BI model combines sales, inventory, reorder, buyer, and cost data. Preparation work included:

- Standardizing product, department, and category fields
- Cleaning missing or inconsistent records where possible
- Creating relationships across non-normalized source tables
- Building measures for sales, COGS, gross margin, margin percentage, inventory value, remaining quantity, and reorder need
- Structuring report pages around the business questions defined by KNFS buyers and managers

## Core KPIs

| Metric | Dashboard Value | Business Meaning |
|---|---:|---|
| Total Sales | $223K | Revenue captured in the analyzed period |
| Cost of Goods Sold | $125K | Direct product cost tied to sales |
| Gross Margin | $87K | Dollar value retained after product cost |
| Gross Margin % | 41% | Profitability ratio for the analyzed period |

## Business Questions Answered

| Question | Dashboard View | Decision Supported |
|---|---|---|
| Which items generate the most revenue? | Top revenue-generating items | Identify strongest product contributors |
| Which areas underperform? | Sales underperformers by department | Focus merchandising or inventory review |
| How much inventory is on hand? | Remaining inventory by quantity and value | Understand stock value and quantity exposure |
| What should be reordered? | Reorder insights | Prioritize out-of-stock or below-threshold items |
| Which items are held too long? | Inventory aging with perishability filter | Reduce waste, free shelf space, and manage capital |
| What are sales and COGS? | KPI cards | Monitor financial performance |
| Which departments lead sales? | Department sales ranking | Guide department-level planning |
| What is the overall store position? | Executive dashboard | Combine financial, sales, and inventory signals |

## Key Insights

- Produce and packaged dry goods are the strongest revenue contributors.
- Several low-performing departments need review for assortment, pricing, or demand fit.
- Reorder analysis highlights items with immediate stockout risk.
- Long-held inventory creates capital and shelf-space pressure, especially where perishable risk exists.
- Gross margin is positive, but the dashboard makes it easier to monitor whether product mix and inventory decisions are protecting profitability.

## Dashboard Design Notes

The final report is designed as an operator-facing dashboard rather than a decorative visualization exercise. The executive page leads with high-level KPIs, then moves into revenue, inventory, reorder, department, and aging views. Supporting pages preserve the original question-by-question analysis for traceability.

Recommended next polish step inside Power BI Desktop:

- Rename question tabs from labels like `1 Q` and `2 Q` to business-readable names such as `Top Products`, `Department Sales`, and `Reorder Risk`.
- Standardize title capitalization across visuals.
- Reduce rounded card styling and shadow intensity for a cleaner professional look.
- Align visual spacing to a consistent grid.
- Add a short data refresh note and period covered.

## Tools and Skills

Power BI, DAX, data modeling, dashboard design, data cleaning, inventory analytics, sales analytics, operational KPI reporting.

## Author

Sairam Jammu  
M.S. Business Analytics, Kent State University
