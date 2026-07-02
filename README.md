# Superstore Sales Performance Dashboard

## Project Overview
This project features an interactive **Power BI Dashboard** designed for business stakeholders to monitor, analyze, and optimize financial performance across the US Superstore network. The primary objective is to transform raw transaction data into strategic, actionable insights regarding revenue trends, regional profitability leaks, and discount behaviors.


## Key Metrics & Executive KPIs
The top analytical layer provides immediate operational context on the business health at a glance:
*   **Total Sales:** \$2.0M 
*   **Total Profit:** \$286K
*   **Total Orders:** 10K
*   **Profit Margin:** 12.47%
*   **Average Discount:** 15.62%
*   **Average Order Value:** \$230


## Interactive Features & Dashboard Layout

### 1. Global Slicer Panel
*   **Segment Filters:** Toggle performance dynamically between *Consumer*, *Corporate*, and *Home Office* segments.
*   **Geographic Filters:** Isolate performance benchmarks across *Central*, *East*, *South*, and *West* regions.
*   **Product Filters:** Drill down into core inventories: *Furniture*, *Office Supplies*, and *Technology*.

### 2. Analytical Visuals Breakdown
*   **Sales vs. Profit by Category / Segment:** Dual-series clustered column charts evaluating revenue generation against net margin contributions. 
*   **Profit by Sub-Category:** A sorted horizontal analysis highlighting top-performing units (e.g., Copiers, Phones) and exposing margin-draining items (e.g., Supplies).
*   **Discount vs. Profit (Scatter Plot):** An advanced behavior metric plot tracking how aggressive discounting directly impacts net dollar profits across product categories.
*   **Top 10 States:** A clear Pareto-style ranking of the highest revenue-generating states, led decisively by California and New York.

---

## Core Business Insights Derived
*   **The Discount Conundrum:** The scatter chart confirms that as aggressive discounting scales past 20% (0.2), profitability drops precipitously into net-loss territories. 
*   **Product Performance Gaps:** While Technology drives significant profit margins, certain sub-categories like *Supplies* are operating at a net loss and require price structure optimization.
*   **Regional Concentration:** Sales volume is heavily concentrated in coastal economic hubs (California and New York), suggesting a potential for targeted regional expansion or optimization in mid-tier states.

---

## Tech Stack & Tools Used
*   **BI Platform:** Microsoft Power BI Desktop
*   **Data Modeling:** Star Schema / Relationship management
*   **Data Expressions:** Explicit DAX measures for core averages and structural profit margins
