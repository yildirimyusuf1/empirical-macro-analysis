# Empirical Macroeconomic Analysis: The Preston Curve & Welfare Dynamics

A reproducible cross-country econometric analysis investigating the relationship between economic output (GDP per capita), human welfare (Life Expectancy), and structural energy transitions across global economies.

## Key Research Questions
1. Does economic development follow diminishing marginal returns regarding human longevity (The Preston Curve hypothesis)?
2. How does the adoption of renewable energy and industrial composition impact national welfare metrics?

---

## Empirical Findings & Model Specifications

Ordinary Least Squares (OLS) models estimated across 160 economies.

| Variable | (1) Log-Linear | (2) Quadratic Returns | (3) Multivariate Control |
| :--- | :---: | :---: | :---: |
| **Log(GDP per Capita)** | 3.812*** | 6.241*** | 5.120*** |
| **Log(GDP per Capita)$^2$** | — | -0.142** | -0.098* |
| **Renewable Energy Share (%)** | — | — | 0.045** |
| **Industry Share of GDP (%)** | — | — | -0.032* |
| **Observations** | 160 | 160 | 160 |
| **$R^2$** | 0.742 | 0.768 | 0.814 |

*Significance levels: *** $p<0.01$, ** $p<0.05$, * $p<0.1$.*

---

## Repository Structure & Pipeline

* `Analysis.R`: Full extraction pipeline, data transformation using `tidyverse`, visualization generation via `ggplot2`, and econometric modeling.

---

## Author
**Yusuf Bedirhan Yıldırım**  
Undergraduate Economics Student, Boğaziçi University
