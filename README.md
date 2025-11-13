# Life Expectancy and GDP (2000–2015)
**Author:** Ann-Christin Borchardt  
**Tools:** Python (pandas, seaborn, matplotlib), Tableau Public  

## Project Overview
This analysis explores how GDP relates to life expectancy across six nations from 2000 to 2015.  
It replicates a classic data-storytelling structure — from data cleaning and transformation to visualization and interpretation.

**Key questions:**
- Has life expectancy increased over time in these countries?  
- Has GDP increased over time?  
- Is there a correlation between GDP and life expectancy?  
- What are the average and distribution patterns of life expectancy?

## Data
- Source: WHO and World Bank datasets (combined as `all_data.csv`)
- Variables: `Country`, `Year`, `GDP`, `Life expectancy (LEABY)`

## Analysis Highlights
- Life expectancy and GDP both increased, though unevenly.
- Developed countries show steady but plateauing trends.
- Emerging economies exhibit rapid, sometimes volatile growth.
- Overall Pearson correlation ≈ 0.79 → clear positive GDP–health link.

## Notebook
Open [`life_expectancy_gdp_GitHub.ipynb`](./life_expectancy_gdp_GitHub.ipynb) to see:
1. Data import and cleaning  
2. Feature transformations (`log10_GDP`)  
3. Trend & correlation analysis  
4. Visual comparisons with `seaborn` facet plots  
5. Findings, conclusions, and generated summary CSVs  

## Visualization (Tableau Public)
Interactive dashboards are available on [Tableau Public](https://public.tableau.com/app/profile/ann.christin.borchardt) → see below for publishing steps.

## Requirements
Tested with Python 3.11  
Install dependencies:
```bash
pip install -r requirements.txt
