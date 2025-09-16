# Poultry Production & Prices in Africa (2000–2021)

## Project Overview
This study explores **poultry production (eggs & chicken meat)**, **producer prices**, and **agricultural CO₂ emissions** in Africa between 2000–2021 using FAOSTAT data.  

The project uncovers key **trends**, **country comparisons** and **relationships** between production, market prices and environmental impact.  
It demonstrates my ability to combine **data science tools** with an **economist’s lens** to generate insights for agribusiness, ESG and policy stakeholders.


## Key Questions
- **Trends:**  
  - How did poultry production evolve across Africa?  
  - How did prices and emissions behave over the same period?  

- **Comparisons:**  
  - Which countries dominate poultry output?  
  - Who grew fastest and how do prices differ across markets?  

- **Relationships:**  
  - Does higher production drive higher emissions?  
  - Do prices influence production volumes (or vice versa)?  
  - Which countries are most efficient (output per unit of CO₂)?  


## Methods & Approach
- **Sanity checks & preprocessing**: filtering, aggregation and handling missing values.  
- **Exploratory trends**: line charts for production, prices and emissions over time.  
- **Comparisons**: country rankings and growth analysis.  
- **Relationships**:  
  - Raw vs. within-country correlations (to distinguish size effects).  
  - Lagged correlations (price-production dynamics).  
  - OLS regression slopes & R² (interpreting marginal impacts).  
  - Efficiency ratios (tonnes per kt CO₂).  


## Key Findings
- Poultry production rose steadily, led by **South Africa, Egypt and Nigeria**.  
- Prices were volatile, reflecting shocks in feed costs, disease and imports.  
- Emissions rose alongside production but **within-country analysis showed efficiency gains matter more than size**.  
- Lagged correlations suggested weak supply response to prices, while production increases tended to soften prices the following year.  
- Efficiency rankings revealed **DRC as a leader** and **Sudan as a laggard**, underscoring structural efficiency gaps.  


## Analysis Implications
- **Agribusiness:** Growth is concentrated in a few markets.
    - For investors and companies, this concentration means there is a clear opportunity to scale in large markets, but also a risk if one major producer faces shocks (disease outbreak, feed crisis, policy shifts), regional supply and prices can be destabilized.  
- **Policy:** Some countries produce far more poultry per unit of CO₂ than others(efficiency leaders vs laggards).
    - Policymakers can use these efficiency benchmarks to guide technology transfer and support for lagging countries.
- **ESG:** Raw correlations show that big producers emit more simply because of size, but efficiency rankings reveal wide differences in emissions per unit of output.
    - Sustainability reporting should highlight efficiency gaps ie which countries or firms deliver more output per unit of CO₂, not just production volumes.


## Tech & Tools
- **Python**: pandas, numpy, matplotlib, seaborn  
- **Data**: FAOSTAT (Production, Producer Prices, Emissions)  
- **Skills shown**: data cleaning, joins/merges, correlations, lag analysis, regression, ratio metrics, visualization, business interpretation  


## Limitations
- Emissions data covers **all agricultural on-farm energy use**, not poultry-specific emissions.  
- Missing years for some countries; no imputation used.  
- Focus is on **correlations and efficiency ratios**, not causal econometric models.  


## Next Steps
- Refine with poultry-specific emission inventories if available.  
- Explore **per-capita consumption** and trade dynamics.  
- Extend to other livestock sectors for a broader food systems view.  

