# 🌾 Maji Ndogo Farm Survey Analysis

## Overview
An exploratory data analysis of 5,654 farms in the Maji Ndogo region, 
investigating what factors influence crop yield and why some farms fail 
to meet their standard yield targets.

## Questions Investigated
- Which crops are most and least cultivated across the region?
- Are farms meeting their standard yield expectations?
- Does pollution level affect yield performance?
- Does rainfall influence how much a farm can produce?
- What drives underperformance in the 11% of farms that fall below standard yield?

## Key Findings
- Most farms (89%) exceed their standard yield
- High pollution suppresses yield potential — extreme overperformance only occurs at low pollution levels
- Peak yields only appear at high rainfall levels
- Rice has the highest median yield; potato has the lowest
- No single factor explains underperformance — it is likely driven by a combination of conditions

## Recommendations
- Prioritise pollution control as a first-line intervention
- Expand rice cultivation in suitable areas
- Investigate maize farms specifically — highest underperformance rate at 13%
- Target investment toward high rainfall zones for maximum yield returns

## Tools Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- SQLite
- Jupyter Notebook

## Dataset
Maji Ndogo Farm Survey — 5,654 farms across 4 related tables:
geographic features, weather features, soil & crop features, and farm management features.

## How to Run
1. Clone the repo
2. Ensure the `.db` file is in the same directory as the notebook
3. Run `maji_ndogo_analysis.ipynb` top to bottom
