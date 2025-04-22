# Superstore Sales Analysis: Data Visualization and Storytelling

## Introduction
This project explores sales and profitability insights using the Superstore dataset. Through Python-based data visualization techniques, the goal is to derive actionable business insights that can aid strategic decision-making for sales, marketing, and logistics teams. The project emphasizes visual storytelling — turning data into a clear business narrative.

## Technical
**Language**: Python (filetype: `.ipynb`)  
**Libraries**: Pandas, Matplotlib, Seaborn  
**Dataset**: Superstore.csv (contains sales and customer-level order information across different markets)

## Content
The notebook conducts exploratory data analysis with a strong focus on visual insights. It helps to:
- Identify profitable and non-profitable product segments
- Understand the effect of discounting on profit
- Track sales patterns across cities, states, and years
- Reveal trends in shipping and customer segments

## Data Fields

| Variable Name       | Description                                              |
|---------------------|----------------------------------------------------------|
| Category            | Product category (e.g., Office Supplies, Technology)     |
| Sub.Category        | Product sub-category (e.g., Paper, Binders)              |
| Customer.ID         | Unique identifier for each customer                      |
| Customer.Name       | Customer's full name                                     |
| Country             | Country where the order was placed                       |
| State               | State within the country                                 |
| City                | City where the order was delivered                       |
| Segment             | Customer segment (Consumer, Corporate, Home Office)      |
| Order.ID            | Unique order identifier                                  |
| Order.Date          | Date the order was placed                                |
| Ship.Date           | Date the order was shipped                               |
| Ship.Mode           | Shipping method (Standard, Second Class, etc.)           |
| Discount            | Discount applied on the order                            |
| Sales               | Sales amount                                              |
| Shipping.Cost       | Shipping charges                                          |
| Market              | Market label (e.g., US)                                   |
| Market2             | Broader market (e.g., North America)                     |
| Year                | Year of the order                                         |
| weeknum             | Week number in the year                                  |


> ⚠️ Note: The column `è®°å½•æ•°` may be an encoding error or placeholder; it should be renamed or removed if unnecessary.

## What We Got From This Project
- Which regions and cities contribute the most to profit?
- Which product categories have high sales but low profit?
- What is the relationship between discounting and profitability?
- How does customer segment behavior differ across years?
- Are there seasonal or weekly trends in order volumes?

## Step Inside The Project
- Load and inspect the dataset
- Data cleaning (e.g., converting dates, handling unusual column names)
- Visualizations:
  - Sales and profit over time (yearly, weekly)
  - Sales by state and city
  - Discount vs profit scatter plots
  - Segment and market-level comparisons
- Insights extraction and business recommendations

## Conclusion
- Certain cities and states contribute disproportionately to profit or loss.
- High discounts often lead to reduced profits, especially in Office Supplies.
- The Consumer segment drives the largest share of sales across all markets.
- Visual storytelling reveals patterns like year-end order surges and unprofitable shipping modes.
- Strategic actions can be taken to optimize product pricing and logistics based on market and segment behavior.
