# Apple Product Pricing and Performance Analysis (2020 to 2026)

## Overview

This project analyses six years of Apple product pricing and performance data collected from Amazon and Flipkart between September 2020 and July 2026, using Microsoft Excel. The dataset was sourced from Kaggle. The analysis covers price trends over time, price and rating differences across product categories, performance during major sales events, stock availability, and which models draw the most consistent customer engagement. The goal was to move beyond a raw listing feed and understand how Apple's pricing and demand actually behave across categories and years.

Built as part of the Vephla University Data Analytics Programme (VEPH/50B/DA084).

## Tools Used

* Microsoft Excel
* PivotTables
* VLOOKUP
* Slicers (Product Category, Model)
* Bar, Line, and Donut Charts
* KPI Cards

## Key Findings

| Metric | Result |
|---|---|
| Records analysed | 80,000 |
| Date range covered | September 2020 to July 2026 |
| Product models tracked | 31 |
| Platforms covered | Amazon, Flipkart |
| Overall average rating | 4.45 |
| Highest rated category | iPhone, 4.451 |
| Highest priced category | Mac, $1,382.49 average |
| Peak year for average price | 2024, $801.93 |
| Top sales event by value | Black Friday, $1,711,159.12 |
| Most reviewed model | iPhone 12 Pro 128GB, 3,723 average reviews per listing |
| Most expensive model | MacBook Pro 14 inch M4 Pro 512GB, $1,826.99 average |
| Stock availability | 68.79% In Stock |

## Performance Summary Tables

### Average Price by Product Category

| Category | Average Price |
|---|---|
| Mac | $1,382.49 |
| iPhone | $758.67 |
| iPad | $573.08 |
| Watch | $398.64 |

### Average Rating by Product Category

| Category | Average Rating |
|---|---|
| iPhone | 4.451 |
| Mac | 4.450 |
| iPad | 4.450 |
| Watch | 4.448 |

### Average Price by Year

| Year | Average Price |
|---|---|
| 2020 | $662.20 |
| 2021 | $722.25 |
| 2022 | $742.50 |
| 2023 | $793.95 |
| 2024 | $801.93 |
| 2025 | $799.67 |
| 2026 (through July) | $759.80 |

### Sales Event Performance (Total Transacted Value)

| Sales Event | Total Value |
|---|---|
| Black Friday | $1,711,159.12 |
| Great Indian Festival | $968,730.80 |
| Big Billion Days | $941,584.27 |
| Prime Day | $710,210.17 |

### Top 5 Most Reviewed Models (Average Reviews per Listing)

| Model | Average Reviews |
|---|---|
| iPhone 12 Pro 128GB | 3,723 |
| MacBook Air M1 256GB | 3,689 |
| Apple Watch Series 6 (44mm) | 3,668 |
| iPhone 12 64GB | 3,667 |
| iPad Air (4th Gen) 64GB | 3,590 |

### Top 10 Most Expensive Models (Average Current Price)

| Model | Average Price |
|---|---|
| MacBook Pro 14 inch M4 Pro 512GB | $1,826.99 |
| MacBook Pro 14 inch M3 Pro 512GB | $1,775.95 |
| MacBook Pro 14 inch M2 Pro 512GB | $1,746.50 |
| MacBook Pro 14 inch M1 Pro 512GB | $1,686.46 |
| iPhone 15 Pro Max 256GB | $1,025.50 |
| iPad Pro 12.9 inch (M2) 256GB | $986.11 |
| iPhone 16 Pro 256GB | $977.04 |
| MacBook Air M2 256GB | $971.62 |
| MacBook Air M3 256GB | $954.90 |
| iPhone 13 Pro Max 256GB | $936.62 |

### Stock Status Distribution

| Status | Share |
|---|---|
| In Stock | 68.79% |
| Out of Stock | 16.84% |
| Low Stock | 14.36% |

## Repository Files

| File | Description |
|---|---|
| `apple_products_pricing_2020_2026.xlsx` | Main deliverable with raw data, PivotTables, and dashboard |
| `Technical_Report.docx` | Full technical report following the Vephla University template |
| `apple_product_pricing_dashboard.png` | Clean screenshot of the full dashboard |
| `README.md` | This file |

## Project Structure

```
Apple-Product-Pricing-Analysis-2020-2026/
│
├── apple_products_pricing_2020_2026.xlsx
├── Technical_Report.docx
├── apple_product_pricing_dashboard.png
└── README.md
```

## Key Insights

* Mac commands the highest average price at $1,382.49, more than triple the average iPhone price, yet all four product categories carry nearly identical average ratings around 4.45.
* Average price climbed steadily from $662.20 in 2020 to a peak of $801.93 in 2024, before easing to $799.67 in 2025 and $759.80 through the first seven months of 2026.
* Black Friday drove far more transacted value than any other sales event, nearly double the next closest event, Great Indian Festival, despite the dataset's heavy Flipkart representation.
* The most reviewed model overall is the iPhone 12 Pro 128GB, an older release outranking every newer model, which likely reflects its longer time on the market as much as active demand.
* Every model in the top 10 most expensive list is either a MacBook Pro or a Pro or Pro Max iPhone, confirming that premium configurations sit at the top of Apple's price ladder across categories.
* Stock availability sits at 68.79% In Stock, with Low Stock (14.36%) nearly as common as Out of Stock (16.84%), suggesting replenishment timing has room to improve.

## Recommendations Summary

* Concentrate promotional budget around Black Friday specifically rather than spreading it evenly across all four sales events.
* Treat price and features, not perceived quality, as the main differentiator across categories, since rating differences between them are negligible.
* Tighten reorder points so Low Stock instances convert to In Stock more consistently before becoming Out of Stock.
* Confirm the most reviewed model ranking against a normalised, tenure adjusted metric before using it in marketing claims.
* Extend the analysis to a complete 2026 calendar year before treating the recent price decline as a confirmed trend.

## Author

**Alaiye Oluwatimileyin**
Student ID: VEPH/50B/DA084
Vephla University Data Analytics Programme
2020 to 2026 Dataset Analysis
