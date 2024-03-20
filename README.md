## exploring child care data in toronto

### introduction

this investigation delves into the data from toronto's child care centers, aiming to understand the patterns and obstacles of accessing quality child care for its citizens. the shortage of licensed or unlicensed child care choices, along with high fees, presents significant challenges for many families in toronto. to address this issue, the provincial administration has committed to creating 100,000 additional child care places between 2016 and 2026.

this study utilizes a large dataset to conduct a thorough analysis of licensed child care facilities in toronto. the dataset, last updated in february 2024, includes vital details regarding the capacity, demographics, and operations of different multi-age child care centers. the main goal is to comprehend the dynamics of child care availability and the difficulties families encounter in obtaining quality child care services.

the dataset comprises two tabs, offering a detailed overview of toronto's licensed child care landscape. the first tab includes an exhaustive list of centers, providing insights into their demographics, classifications, locations, and daily capacity information. the second tab serves as a reference guide, offering a clear understanding of the meanings behind each feature included in the dataset.

### research question

the primary research question addressed in this analysis is: **"are there significant differences in the occupancy rates of child care centers based on their operating space (commercial, non-profit, or public), and do these differences manifest across various centers in toronto?"**

### data exploration

to initiate the analysis, summary statistics were calculated for the dataset, including information on various child care centers, demographic details, and capacity metrics.

| variable    | min | mean | max | 25th | median | 75th | iqr  |
|-------------|-----|------|-----|------|--------|------|------|
| igspace     | 0   | 3.9  | 30  | 0.0  | 0.0    | 10.0 | 10.0 |
| tgspace     | 0   | 11.6 | 90  | 0.0  | 10.0   | 15.0 | 15.0 |
| pgspace     | 0   | 24.26| 144 | 16.0 | 24.0   | 32.0 | 16.0 |
| kgspace     | 0   | 14.26| 130 | 0.0  | 0.0    | 26.0 | 26.0 |
| sgspace     | 0   | 21.66| 285 | 0.0  | 0.0    | 30.0 | 30.0 |
| totspace    | 6   | 75.67| 402 | 43.0 | 62.0   | 97.0 | 54.0 |

### data cleaning and wrangling

the raw dataset comprises 17 columns with 1,063 entries. minimal data cleaning was required for the analysis.

- missing values were observed in the 'bldgname' column, with 715 non-null entries out of 1,063.

### one-way anova

a one-way anova was conducted to investigate differences in total space based on the operating space (auspice). post-hoc tests revealed specific group differences, and assumption testing was performed.

### results

the analysis revealed notable differences in child care space allocation based on operating space (commercial, non-profit, and public). various factors, including organizational strategies, funding structures, and regulatory frameworks, may contribute to these differences. additional investigation is warranted to disentangle the contributing components and identify solutions for optimizing child care space allocation.


### Conclusion

By exploring data from Toronto's child care centers, valuable insights were gained into the distribution and utilization of child care spaces. This insight can inform stakeholders and policymakers in making informed decisions to enhance child care services and address the needs of the community.
