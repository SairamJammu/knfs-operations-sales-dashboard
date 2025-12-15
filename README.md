# Kent Natural Food Store – Operations & Sales Dashboard
![Dashboard Overview](Screenshots/overview-dashboard.png)


##  Project Overview
This project involved designing and developing an **interactive Power BI dashboard** for **Kent Natural Food Store (KNFS)**, a community-owned grocery co-op specializing in organic, local, and environmentally sustainable products.

The goal was to provide **clear visibility into sales, inventory, and operational performance** to support better purchasing, replenishment, and inventory management decisions by department buyers.

This project was completed as part of the **Data Visualization (BA-54050)** course in the MS Business Analytics program at Kent State University.

---

##  Business Context
KNFS operates across **21 departments** with **7 buyers**, each responsible for pricing and ordering within their assigned categories.  
Although KNFS uses a Point-of-Sale system, historical data had **not been systematically analyzed**, leading to limited insight into:
- What items to reorder
- When to reorder
- How much inventory to hold
- Which products and departments drive profitability

The dashboard addresses these gaps by transforming raw POS, inventory, and cost data into **actionable decision-support visuals**.

---

##  Business Questions Addressed
The dashboard directly answers the following operational and sales questions:

1. Which items are selling the most?
2. Which items are selling the least (by department)?
3. How much inventory do we have (by quantity and value)?
4. Which items should be reordered soon, and in what quantity?
5. Which items have been in inventory the longest (with focus on perishables)?
6. What are total sales and cost of goods sold (COGS)?
7. Which departments generate the most sales?
8. What is the overall sales, cost, and gross margin performance of the store?

---

##  Data Sources
The analysis integrates multiple datasets provided by KNFS:

- **Sales Transactions** (Jan 1 – Apr 16, 2024)
- **Inventory Listings** (snapshot as of Apr 16, 2024)
- **Below-Reorder Inventory Reports**
- **Department-level Cost of Goods Sold**
- **Department Markup Rates**

Because the data was not fully normalized, significant preprocessing and transformation were required before analysis.

---

##  Data Preparation & Modeling
Key data engineering steps included:

- Cleaning and standardizing product names, categories, and departments
- Resolving missing values and inconsistent formatting
- Creating relationships across sales, inventory, and cost tables
- Developing calculated fields and measures using **DAX**, including:
  - Total Sales
  - Cost of Goods Sold
  - Gross Margin ($ and %)
  - Inventory Value
  - Inventory Aging
  - Reorder Quantity Requirements

These steps enabled dynamic and accurate dashboard interactions.

---

##  Dashboard Features
The Power BI dashboard includes:

- KPI cards for Total Sales, COGS, Gross Margin
- Top and bottom performing products and departments
- Inventory quantity and value analysis
- Reorder alerts for items below reorder point
- Inventory aging analysis with emphasis on perishables
- Interactive filters for departments, categories, and products

Each visual was designed to directly answer a specific buyer or management question.

---

##  Key Insights & Recommendations
- **Produce and Packaged Dry Goods** drive the highest sales and should be prioritized for availability.
- Several products are **below reorder points**, indicating risk of stockouts.
- Certain items have been held in inventory for **over 300 days**, tying up capital and shelf space.
- The store achieves a **gross margin of ~41%**, indicating healthy overall performance.
- Low-performing departments (e.g., Vitamins, some specialty categories) may benefit from promotions, assortment reduction, or pricing review.

---

##  Limitations & Future Enhancements
- Customer-level data was unavailable, limiting repeat-purchase analysis.
- Shelf-space dimensions were not provided, preventing spatial sales optimization.
- Predictive demand modeling could further improve reorder decisions if historical trends are extended.

Future iterations could incorporate:
- Customer repeat behavior
- Predictive purchasing models
- Price sensitivity simulations
- Shelf-space efficiency analysis

---

##  Tools & Technologies
- **Power BI**
- **DAX**
- **Excel / CSV datasets**
- Data cleaning & transformation techniques

---

##  Team
Group Project – Data Visualization  
- Bhavya Jeevani Thandu  
- **Sairam Jammu**  
- Eric Draper  

---

## 👤 Author Focus
This repository highlights my contribution to **data modeling, dashboard design, KPI development, and insight interpretation**, with a focus on using visualization to support real-world business decisions.
