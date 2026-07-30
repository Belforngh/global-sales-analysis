You can check my project [here](https://docs.google.com/spreadsheets/d/1TGhNLXBLGESPUQKz9c63-RP0w-rZkD04_nmZlMeCdt4/edit?usp=sharing)
**Global Sales Analysis (Google Sheets)**

Analysis of a retail sales dataset covering 1,246 orders across 45 countries and 12 product categories, from 2010 to 2017. Built in Google Sheets, exported to Excel format.

**Goal**

The aim was to go beyond basic totals and test a few assumptions that seem intuitive but are not always true: does order priority actually affect processing speed or profitability, does the sales channel matter, does the season affect margin, and which countries and categories really drive the result.

**Data**

Order level records: order date, ship date, order priority, country, product type, sales channel (online/offline), units sold, unit price, unit cost, revenue, cost and profit. Country level population and region/subregion data were joined in separately.

**Tools and methods**

Google Sheets / Excel. SUMIFS, SUMPRODUCT, XLOOKUP, IF with AND/OR, FILTER, ARRAYFORMULA, pivot tables and pivot charts, slicers. Key visuals combined on one Mini Dashboard sheet.

**Key findings**

Overall 1,246 orders, 45 countries, total profit of about 473.7 million.

Product categories drive very different margins Margin ranges widely by category, from 13.6 percent on Meat up to 67.2 percent on Clothes. Office Supplies is the largest category by revenue (about 378.7 million) but sits at a relatively modest 19.4 percent margin, while Clothes is a smaller category by revenue but by far the most profitable per dollar sold. This is the clearest actionable signal in the dataset: revenue volume and margin do not move together.

Sales channel barely matters Online and offline are nearly split down the middle: 625 vs 621 orders, 789.0 million vs 810.0 million in revenue, 235.2 million vs 238.5 million in profit. No meaningful channel advantage in this dataset.

Order priority affects speed a little, but not profitability Average processing time is somewhat lower for High and Critical priority orders (about 24 days) than for Low and Medium (about 25 to 26 days), so priority does have a small, real effect on speed. Profit margin, however, stays flat across all four priority levels (29.5 percent to 29.8 percent). Priority speeds things up slightly but does not change how profitable an order is.

Season affects volume, not margin Order counts and revenue shift somewhat by season, but margin stays essentially flat across all four seasons (around 29.5 percent to 29.8 percent), the same pattern seen with order priority.

Country level spread Orders per country range from 13 (Monaco) to 40 (Andorra and San Marino, tied). Country level margin also varies more than priority or season, from roughly 25 percent to 40+ percent depending on the country, suggesting geography matters more to profitability than operational fields like priority or channel.

Regional product preferences differ The top selling product varies by region: Meat leads in Asia, Office Supplies leads in Europe. Within Europe specifically, Office Supplies is the top product in 7 countries (Austria, Bosnia and Herzegovina, France, Croatia, Lithuania, Portugal, Slovakia), while Cosmetics leads in 6 (Albania, Switzerland, Iceland, Malta, Sweden, Ukraine). No single category dominates across the board, country level preference is fairly fragmented.

**Dashboard preview**

<img width="938" height="698" alt="image" src="https://github.com/user-attachments/assets/ec368627-c533-4a5d-bb86-0f9cb1034741" />
<img width="1100" height="644" alt="image" src="https://github.com/user-attachments/assets/6a0bfc5a-7fae-4fc0-9fb4-200e467bd34b" />
<img width="938" height="632" alt="image" src="https://github.com/user-attachments/assets/3e4eb905-6a11-4c60-8d81-be1e9bbe6099" />



**Files**
Global sales analysis: full workbook with raw data, calculations and dashboard

Live version (view only): https://docs.google.com/spreadsheets/d/1TGhNLXBLGESPUQKz9c63-RP0w-rZkD04_nmZlMeCdt4/edit?usp=sharing
