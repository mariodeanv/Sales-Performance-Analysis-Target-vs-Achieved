# Sales Performance Analysis — Target vs Achieved

## Project Overview

This project looks at how a sales team performed against their monthly targets
across different regions, products, and reps. A synthetic sales dataset is
generated inside the notebook (no external files needed), then analyzed and
visualized end-to-end using Python, pandas, and Seaborn.

### Questions this project answers
- How does actual sales performance (**Achieved**) compare to **Target** in each region?
- Which sales reps are exceeding, meeting, or falling short of their targets?
- How is the team distributed across performance tiers (Excellent, Good, Average, Below Target)?
- Which product categories are most consistent vs. most volatile in hitting target?
- Is there a relationship between Target size and Achieved amount?

### Graphs

**1. Target vs Achieved by Region**
Grouped bar chart comparing total target and actual sales per region.

C:\Users\mario\AppData\Local\Temp\d437b498-a0b7-4fb5-870c-4c2ea039be10_sales_performance_analysis_project_1.zip.e10\sales_project\images\target_vs_achieved_by_region.png

**2. % Achieved by Sales Rep**
Bar chart ranking reps, with a 100% target reference line.

![% Achieved by Sales Rep](images/pct_achieved_by_rep.png)

**3. Performance Tier Distribution**
Count plot showing how many records fall into each performance tier.

![Performance Tier Distribution](images/performance_tier_distribution.png)

**4. % Achieved by Product**
Box plot showing the spread and consistency of performance per product category.

![% Achieved by Product](images/pct_achieved_by_product.png)

**5. Correlation Heatmap**
Relationship between Target, Achieved, and % Achieved.

![Correlation Heatmap](images/correlation_heatmap.png)

## What it covers
| Lists & a tuple | Sales reps / products as lists, regions as a tuple |
| `for` loops | Generating records, classifying performance, printing insights |
| `if / elif / else` | Performance tier classification |
| Functions | Reusable performance-classification logic |
| numpy | Quick average calculation (`np.mean`) |
| pandas | DataFrame creation, `groupby`, aggregation, CSV export |
| seaborn | Bar charts, box plot, count plot, heatmap |



