Historical Sales and Inventory Analysis


This project leverages Excel to analyze historical sales and inventory data, sourced from Kaggle’s Historical Sales and Active Inventory dataset https://www.kaggle.com/datasets/flenderson/sales-analysis?resource=download. Through Excel’s data analysis features, this project uncovers trends in sales performance, pricing strategies, and marketing effectiveness across different product types and years.

Dataset Overview

Key columns in the dataset include:

Order: Order number (identifier).

SKU_number: Product identifier.

SoldFlag / SoldCount: Binary and quantity indicators of sales.

MarketingType: Marketing approach applied to the product.

StrengthFactor: Measure of the product’s strength in the market.

PriceReg / LowNetPrice: Regular and lowest net prices.

ReleaseYear: Year the product was introduced.

Project Steps and Key Analyses

Sorting & Filtering

Goal: Organize data by price, release year, and sales to highlight top products and trends.

Instructions: Sort by PriceReg, apply a custom sort by ReleaseYear and SoldCount, and filter for top products by StrengthFactor.

Insights: Identifies top products and reveals pricing trends over time.

Pivot Table Analysis

Goal: Use pivot tables to analyze sales by marketing strategy and release year.

Instructions: Set up MarketingType as rows, ReleaseYear as columns, and SoldCount as values. Add a calculated field for average PriceReg per MarketingType.

Insights: Highlights how different marketing strategies impact sales across release years.

Charting

Goal: Visualize sales by marketing type and key release years using column and treemap charts.

Instructions: Create column charts showing SoldCount by MarketingType and apply slicers for interactive filtering.

Insights: Reveals effective marketing strategies and product sales distribution over time.

Conditional Functions (SUMIF, AVERAGEIF, COUNTIF)

Goal: Summarize sales volume, average prices, and strength metrics based on set conditions.

Instructions: Use SUMIF for post-2010 SoldCount, AVERAGEIF for prices of sold products, and COUNTIF to find products with high StrengthFactor.

Insights: Summarizes product performance based on specific conditions.

Lookup Functions

Goal: Retrieve specific data points for further analysis.

Instructions:
VLOOKUP: Use to find PriceReg for specific SKU_number.

INDEX and MATCH: Locate LowUserPrice based on SKU_number.

HLOOKUP: Retrieve SoldCount by ReleaseYear across multiple rows.

Insights: Enables quick access to targeted information, improving efficiency in data retrieval.

Treemap Chart

Goal: Visualize the distribution of sales across different marketing types.

Instructions: Create a treemap based on MarketingType and SoldCount, with color coding for different sales volumes.

Insights: Illustrates concentration of sales within each marketing strategy.

Macros

Goal: Automate repetitive tasks for efficiency.

Instructions: Record a macro to filter the dataset for sold products (SoldFlag = 1). 

Insights: Macros save time by automating routine filtering and sorting processes.
