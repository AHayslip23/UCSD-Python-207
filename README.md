# UCSD Python 207

Coursework for UC San Diego's DSE 207R (Python for Data Analysis, Fall 2023): a mini project on world happiness data and an end-to-end final project on NBA game statistics.

## Repository Contents

| File | Description |
|---|---|
| `Alex Hayslip Final Project 2023.ipynb` | Final project: NBA games 2004–2022, covering cleaning, EDA, k-means clustering, regression and classification |
| `Alex Hayslip Mini Project Happiness Data Set .ipynb` | Mini project: exploratory analysis of the 2016 World Happiness Report |

## Commit History

### `08362aa`: Final project (2025-09-05)
- **Added the final project notebook.**
- **Data:** merged two NBA datasets of regular-season games and game statistics, 2004–2022.
- **Cleaning:** fixed inconsistent formatting, such as the minutes column, and filtered out invalid records.
- **EDA:**
  - histograms of field goals attempted, made and percentage (FGA, FGM, FG_PCT)
  - scatterplots of shooting stats, which showed only weak linear relationships
- **K-means clustering:** grouped field goal attempts and field goal percentage per game into above-, at- and below-average performance groups.
- **Multiple regression:** predicted points scored with an R² of 99.6%.
- **Classification:** a decision tree and a random forest predicted whether a game took place during a shortened season. FG_PCT and FGA were the most important features.
- **Summary:** findings across all five parts.

### `bafc660`: Mini project, happiness dataset (2025-09-05)
- **Added the mini project notebook.**
- **Data:** the 2016 World Happiness Report (157 countries, 13 columns).
- **Cleaning:** checked data quality (no duplicates or nulls, six zero values) and dropped the happiness rank column.
- **Objective-based EDA:**
  - family has the strongest correlation with happiness score
  - in Western Europe, freedom vs. trust in government (corruption) were compared for their association with happiness
- **Ethics:** discussed how reliable the trust (government corruption) measure is.

## Tools
Python, pandas, NumPy, scikit-learn, matplotlib, seaborn, Jupyter Notebook
