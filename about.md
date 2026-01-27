# Statistical Modeling of Dengue Cases in Pernambuco, Brazil

This repository contains the data, code, and supplementary materials supporting the manuscript:

**Statistical modeling of Dengue cases in the state of Pernambuco, Brazil:  
a panel data approach using Zero-Inflated Negative Binomial regression**

Submitted to: **Science of The Total Environment**

---

## Abstract

Dengue is one of the most prevalent arboviral diseases in Brazil, exhibiting a highly heterogeneous spatial and temporal distribution. In the state of Pernambuco, several municipalities report prolonged periods with zero cases, while others experience recurrent outbreaks. To address these characteristics, this study applies panel data regression models with excess zeros and overdispersion, covering 185 municipalities from January 2020 to June 2023.

After rejecting the equidispersion assumption, a Zero-Inflated Negative Binomial (ZINB) model with random effects was selected using the `glmmTMB` package in R. Climatic variables were modeled in the count component, while structural and sanitation-related variables were incorporated into the zero-inflation mechanism.

The results indicate that maximum temperature and lagged precipitation are significant predictors of dengue incidence. Structural variables such as access to piped water and solid waste collection increase the probability of structural zeros, suggesting that improved sanitation reduces dengue occurrence. Although focused on Pernambuco, the proposed framework is transferable to other regions with similar epidemiological and climatic contexts.

---

## Methodological Overview

The research workflow was structured into four main stages:

1. Literature review and conceptual framing  
2. Data collection and preprocessing  
3. Model estimation and selection  
4. Statistical validation and interpretation  

The analysis integrates climatic, epidemiological, and sanitation data using a longitudinal and cross-sectional perspective, ensuring robustness and policy relevance.

---

## Data Sources

- Dengue cases: DATASUS / SINAN  
- Climatic variables (temperature, precipitation, humidity): APAC  
- Sanitation indicators (water supply, sewage, waste collection): SNIS  
- Urban solid waste data: CPRH (via Access to Information Law requests)

---

## Code and Software

- Language: R (version 4.3.2)  
- Main package: glmmTMB  
- Additional packages: dplyr, tidyr, ggplot2, sf, overdisp  

All scripts are fully reproducible and documented.

---

## Repository Structure

