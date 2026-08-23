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

<img width="887" height="485" alt="image" src="https://github.com/user-attachments/assets/d8f26f60-0e31-4a1f-8841-1ace57d306f9" />

**2. % Achieved by Sales Rep**
Bar chart ranking reps, with a 100% target reference line.

<img width="887" height="484" alt="image" src="https://github.com/user-attachments/assets/e3a4c019-dbef-44f6-937c-8b5dd2ec5fa4" />

**3. Performance Tier Distribution**
Count plot showing how many records fall into each performance tier.

<img width="688" height="490" alt="image" src="https://github.com/user-attachments/assets/e4cf4467-9808-4fbd-88f7-a69a1116c9f0" />

**4. % Achieved by Product**
Box plot showing the spread and consistency of performance per product category.

<img width="887" height="488" alt="image" src="https://github.com/user-attachments/assets/913e26ec-1ca2-4c3e-ae64-20a8cd0ad57a" />

**5. Correlation Heatmap**
Relationship between Target, Achieved, and % Achieved.

<img width="523" height="389" alt="image" src="https://github.com/user-attachments/assets/ab2f790a-4d5d-4805-9460-bec857cdbcc7" />

## What it covers
| Lists & a tuple | Sales reps / products as lists, regions as a tuple |
| `for` loops | Generating records, classifying performance, printing insights |
| `if / elif / else` | Performance tier classification |
| Functions | Reusable performance-classification logic |
| numpy | Quick average calculation (`np.mean`) |
| pandas | DataFrame creation, `groupby`, aggregation, CSV export |
| seaborn | Bar charts, box plot, count plot, heatmap |



