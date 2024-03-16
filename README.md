## Exploring Child Care Data in Toronto

### Introduction

This investigation delves into the data from Toronto's child care centers, aiming to understand the patterns and obstacles of accessing quality child care for its citizens. The shortage of licensed or unlicensed child care choices, along with high fees, presents significant challenges for many families in Toronto. To address this issue, the provincial administration has committed to creating 100,000 additional child care places between 2016 and 2026.

This study utilizes a large dataset to conduct a thorough analysis of licensed child care facilities in Toronto. The dataset, last updated in February 2024, includes vital details regarding the capacity, demographics, and operations of different multi-age child care centers. The main goal is to comprehend the dynamics of child care availability and the difficulties families encounter in obtaining quality child care services.

The dataset comprises two tabs, offering a detailed overview of Toronto's licensed child care landscape. The first tab includes an exhaustive list of centers, providing insights into their demographics, classifications, locations, and daily capacity information. The second tab serves as a reference guide, offering a clear understanding of the meanings behind each feature included in the dataset.

### Research Question

The primary research question addressed in this analysis is: **"Are there significant differences in the occupancy rates of child care centers based on their operating space (Commercial, Non-Profit, or Public), and do these differences manifest across various centers in Toronto?"**

### Data Exploration

To initiate the analysis, summary statistics were calculated for the dataset, including information on various child care centers, demographic details, and capacity metrics.

| Variable    | Min | Mean | Max | 25th | Median | 75th | IQR  |
|-------------|-----|------|-----|------|--------|------|------|
| IGSPACE     | 0   | 3.9  | 30  | 0.0  | 0.0    | 10.0 | 10.0 |
| TGSPACE     | 0   | 11.6 | 90  | 0.0  | 10.0   | 15.0 | 15.0 |
| PGSPACE     | 0   | 24.26| 144 | 16.0 | 24.0   | 32.0 | 16.0 |
| KGSPACE     | 0   | 14.26| 130 | 0.0  | 0.0    | 26.0 | 26.0 |
| SGSPACE     | 0   | 21.66| 285 | 0.0  | 0.0    | 30.0 | 30.0 |
| TOTSPACE    | 6   | 75.67| 402 | 43.0 | 62.0   | 97.0 | 54.0 |

### Data Cleaning and Wrangling

The raw dataset comprises 17 columns with 1,063 entries. Minimal data cleaning was required for the analysis.

- Missing values were observed in the 'BLDGNAME' column, with 715 non-null entries out of 1,063.

### One-way ANOVA

A one-way ANOVA was conducted to investigate differences in total space based on the operating space (AUSPICE). Post-hoc tests revealed specific group differences, and assumption testing was performed.

### Results

The analysis revealed notable differences in child care space allocation based on operating space (commercial, non-profit, and public). Various factors, including organizational strategies, funding structures, and regulatory frameworks, may contribute to these differences. Additional investigation is warranted to disentangle the contributing components and identify solutions for optimizing child care space allocation.

### Conclusion

By exploring data from Toronto's child care centers, valuable insights were gained into the distribution and utilization of child care spaces. This insight can inform stakeholders and policymakers in making informed decisions to enhance child care services and address the needs of the community.
