# Panel-Data-Analysis-Research-Paper
The Non-Linear Impact of Leverage on Firm Performance: A Panel Data Analysis of Indian Manufacturing Firms
# The Non-Linear Impact of Leverage on Firm Performance
## A Panel Data Analysis of Indian Manufacturing Firms (2016–2025)

### Project Overview
This research investigates the relationship between financial leverage and profitability (ROA) among BSE-listed Indian manufacturing firms. Using a balanced panel dataset, the study tests the non-linear predictions of Trade-off Theory against the empirical reality of the Indian market over a 10-year horizon.

### Methodology & Data
* **Sample Size:** 78 BSE-listed firms resulting in 780 firm-year observations.
* **Data Source:** Capitaline corporate database.
* **Time Frame:** 2016 to 2025.
* **Data Treatment:** All ratio variables were winsorized at the 1st and 99th percentiles to mitigate the influence of extreme values and financial distress.

### Model Specifications
The analysis utilizes a **Two-Way Fixed Effects (TWFE)** model, selected after a Hausman Test (chi^2(7) = 53.86, p < 0.001$) rejected Random Effects.

**Regression Equation:**
ROA_it = β₀ + β₁LEV_it + β₂LEV²_it + β₃SIZE_it + β₄TANG_it + β₅GROWTH_it + β₆LIQ_it + α_i + λ_t + ε_it 

### Key Findings
* **Negative Linear Impact:** Leverage (LEV) has a significant negative effect on ROA ($\beta = -0.1679, p = 0.001$). A one-unit increase in the debt-to-asset ratio leads to a 16.79 percentage point drop in profitability.
* **No Non-Linearity:** The squared leverage term ($LEV^2$) was statistically insignificant ($p = 0.307$) in the full sample, suggesting no "optimal" debt level exists within the observed range.
* **Growth is King:** Sales growth is the most consistent and dominant driver of firm profitability across all models.
* **Post-COVID Shift:** A structural shift occurred post-2020, where the relationship became strictly negative linear, likely due to higher borrowing costs and tighter financial conditions.

### Repository Contents
* 'panel regression.ipynb': Jupyter Notebook containing the Python implementation for panel data estimation and diagnostic tests.
* 'PDA - RP FINAL.pdf': Full research paper detailing the study, methodology, and findings.

### Tech Stack
`Python` | `Pandas` | `Linearmodels` | `Statsmodels` | `Matplotlib`
