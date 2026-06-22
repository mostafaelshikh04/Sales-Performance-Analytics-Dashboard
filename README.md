# Sales Performance Analytics Dashboard

## Overview
An end-to-end business intelligence solution built in Excel using Power Pivot, 
analyzing $2.3M in retail sales data across 4 years (2014–2017).

## Dataset
- 7 interconnected tables: Orders, Returns, People, Shipping Cost
- 5,000+ transactions
- 4 product categories: Furniture, Office Supplies, Technology, and sub-categories

## Architecture
Star Schema in Power Pivot:
- **Fact Table**: Orders
- **Dimensions**: People, Shipping_Cost, Returns

## Key Metrics
| Metric | Value |
|--------|-------|
| Total Sales | $2,297,201 |
| Net Sales | $2,116,697 |
| Returns | $180,504 |
| Discounts | $297,687 |
| Total Customers | 793 |

## Features
- Interactive slicers (City, Person, Category, Returned status)
- KPI cards for top-level metrics
- Drill-down charts: Sales by Category, Region, State, City
- Time-series trend analysis (2014–2017)

## Tools
- Excel | Power Pivot | Power Query | DAX

## Insights
1. Technology category leads revenue ($836K)
2. West region strongest ($725K), South needs attention ($391K)
3. Returns represent 7.8% of sales — optimization opportunity
4. Discounts may be eroding margins in specific regions

## Recommendations
- Reduce discounting in low-margin regions
- Increase Technology inventory in West region
- Investigate South region underperformance
- Implement returns root-cause analysis

## Author
[Mostafa Mahmoud] — Junior Data Analyst
