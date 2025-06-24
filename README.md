## Climate & Catastrophe: A Data-Driven Analysis of Rising Temperatures, Natural Disasters, and their Economic Toll

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

### Investigating the Relationship between Global Warming and Natural Disasters:

This project delivers a thorough exploratory data analysis to explore how rising global temperatures relate statistically to the increasing frequency of natural disasters and their growing economic costs.

### Using Python and core data science libraries (Pandas, Matplotlib, Seaborn, and SciPy), I analyzed three major datasets:

-> Global land and sea temperatures from 1750 to 2015
-> Recorded natural disasters by type from 1900 to 2018
-> Associated economic losses during the same period

### Analytical Workflow:

a) Data Preparation & Cleaning: I processed large datasets and calculated annual temperature anomalies based on the 1951–1980 baseline to make warming trends visually clear.

b) Trend Visualizations: I produced visual tools such as time-series plots of temperature changes and stacked bar charts of disaster counts to identify rising trends in both climate data and disaster frequency.

c) Correlation Analysis: A detailed correlation matrix and heatmap were developed to evaluate relationships between variables. I also separated climate-driven disasters (like storms and floods) from non-climate events (like earthquakes) to enhance focus.

d) Economic Normalization: To account for global economic growth, disaster damage figures were normalized using yearly World GDP. This adjustment allowed for a clearer understanding of the proportional economic impact over time.

e) Statistical Testing: I applied the Shapiro-Wilk test to check for normality in the data and used both Pearson and Spearman tests to confirm the statistical strength of the relationships observed.

### Key Results:

1) There is a very strong and statistically significant correlation (ρ ≈ 0.89) between rising global temperatures and the frequency of climate-related disasters.

2) A moderate but significant positive correlation (ρ ≈ 0.45) was also found between temperature increases and normalized disaster-related economic losses. This indicates that while costs are rising, much of it reflects the growing global infrastructure at risk.

3) The findings also support the “Reporting Bias Hypothesis”—improved detection and global reporting have contributed to the observed rise in documented geophysical and climate-related disasters.

### Conclusion

This analysis presents solid, data-backed evidence that our warming climate is closely linked to a significant increase in climate-related disasters, which are having a steadily growing impact on the global economy.

## Technology Tools Used: 
Python, Pandas, NumPy, Matplotlib, Seaborn, SciPy.
