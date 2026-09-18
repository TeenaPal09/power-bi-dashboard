# Power BI Superstore Sales Performance Dashboard

## Objective
An interactive Power BI dashboard built on a real-world sales dataset to analyze business performance and generate actionable business insights across regions, product categories, customer segments, and shipping preferences.

## Dataset
- **Source:** Superstore Sales Dataset (Kaggle)
- **Fields:** Ship Mode, Segment, Country, City, State, Postal Code, Region, Category, Sub-Category, Sales, Quantity, Discount, Profit (13 columns)
- **Note:** This version of the dataset does not include Order Date or Product Name fields. *Sales by Ship Mode* and *Top 10 Cities by Sales* were used in place of a monthly trend and top-products view to work within the available fields.

## Tools Used
Microsoft Power BI Desktop, DAX

## Dashboard Highlights
- 13 visuals including KPI cards, category/sub-category/state/city breakdowns, regional profit analysis, customer segment analysis, a discount-vs-profit scatter chart, and sales distribution
- 5 DAX measures (Total Sales, Total Profit, Total Quantity, Sum of Discount, Count of Sales)
- Interactive slicers for Region, Category, and Segment

## Key Insights
- Sales are heavily concentrated in a handful of states, led by California and New York
- The West region leads in both sales (31.6%) and profit, with Central and South trailing
- Standard Class is the dominant shipping mode, suggesting customers prioritize cost over speed
- The Consumer segment drives the most sales; Home Office represents a growth opportunity
- Higher discount levels are associated with lower profit, particularly at higher discount percentages
- Sales values are heavily right-skewed, with most transactions low-value and a few high-value orders driving totals

Full write-up with all 8 insights and recommendations is in the [project report
