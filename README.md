# Sales-Dashboard
# Sales Performance Dashboard (Power BI)

An interactive Power BI dashboard that tracks sales, orders and profitability for a tech-accessories business across regions, product categories and customer segments.

![Dashboard overview](screenshots/dashboard_overview.png)

## Business Questions Answered

- How much revenue and profit is the business generating, and at what margin?
- How does profit change month by month?
- Which product categories and individual products contribute most to net sales?
- How do results differ by region, customer segment and year?

## Key Metrics

| Metric | Value |
|---|---|
| Total Sales | 2.96M |
| Net Sales | 2.96M |
| Total Orders | 236 |
| Gross Profit | 1.18M |
| Profit Margin | ~40% |
| Average Order Value | ~12.5K (Total Sales / Total Orders) |

## Dashboard Features

- **KPI cards:** Total Sales, Net Sales, Total Orders, Gross Profit and Profit Margin %.
- **Slicers:** filter the whole report by Year (2025, 2026), Region (East, North, South, West), Product Category and Customer Segment (Enterprise, Mid-Market, SMB).
- **Gross Profit trend:** line chart of gross profit by year-month.
- **Net Sales by Category:** pie chart across Accessories, Audio, Connectivity, Office Setup and Video.
- **Net Sales by Product:** donut chart across Headset, Keyboard, Laptop Stand, USB-C Hub, Webcam and Wireless Mouse.

## Insights

- The business earns roughly a **40% gross margin** on 2.96M in sales across 236 orders.
- Net Sales equals Total Sales, so no discounts or returns are deducted in this dataset.
- Sales are spread across 5 categories and 6 products. <!-- Add which category/product leads once the visuals are final -->
- <!-- Add your trend insight here, e.g. how monthly gross profit moves from 2025 to 2026 -->
- <!-- Add a region or customer-segment insight here -->

## Tools & Skills Used

- **Power BI Desktop** for report design and interactivity
- **Power Query** for data cleaning and shaping
- **DAX** for measures (Total Sales, Net Sales, Gross Profit, Profit Margin %)
- **Data modelling** with fact and dimension tables (Products, Region, Customer Segment, Date)

## Repository Structure

```
├── project_practice.pbix   # Power BI report file
├── data/                   # Source data files
├── screenshots/            # Dashboard images
└── README.md
```

## How to Use

1. Download `project_practice.pbix` from this repository.
2. Open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free, Windows).
3. Use the slicers at the top to filter by year, region, category and segment.

## Author

**Raj Dahiwadkar**
[GitHub](https://github.com/rajd12) · [LinkedIn](https://www.linkedin.com/in/rajdahiwadkar)
