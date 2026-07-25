# Power-BI-Sales-Performance-Dashboard
Interactive Sales Performance Dashboard built using Power BI, DAX, and Power Query.
# Sales & Product Performance Dashboard - Power BI

## Project Overview
Analyzed 3000+ orders from Jul 2024 to Jun 2025 to drive business decisions across Sales and Product domains. Total Revenue: $76.51M

## Key Features
- *Sales Analytics*: Total Sales, Profit, Margin %, Quantity, Orders, Monthly Trend
- *Product Analytics*: Category-wise Sales, Top 3 Products, SubCategory analysis
- Drill-through Navigation: Navigate from summary visuals to a detailed Product Details page for in-depth analysis
- Dynamic Dashboard Title
- Report Page Tooltip for "Total Profit By Category" visual for enhanced category insights
- *Interactivity*: Date Slicer, Category Slicer, Region Slicer, Reset Filters
- *Tools*: Power BI, DAX Measures, Data Modeling, Power Query
- Bookmark Navigation: Implemented a bookmark-based Reset Filters button for quick dashboard reset.
 ## Key Insight
1. *Revenue*: $76.51M Total Sales with 29.74% Profit Margin
2. *Top Performer*: West Region - 37.97% of total sales. Technology category most profitable
3. *Product Trend*: Laptops and Keyboards drive highest revenue. Peak sales in Dec 2024
## Data Modeling
- Custom DateTable: 01-07-2024 to 30-06-2025 with Year, Quarter, Month
- Connected DateTable to Orders[OrderDate] for time intelligence
- Calculated Measures: Total Sales, Total Profit, Total Orders, Total Quantity, Profit Margin %
  
