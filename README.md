# Modeling dengue incidence under excess zeros: evidence from a tropical region of the Global South


This repository contains the data, code, and supplementary materials supporting the manuscript:

**Modeling dengue incidence under excess zeros: evidence from a tropical region of the Global South**

Submitted to: **International Journal of Biometeorology**

---

## Abstract

Dengue is one of the most prevalent arboviral diseases in Brazil, with a highly heterogeneous spatial distribution. In Pernambuco, there is substantial variation among mesoregions: while some municipalities report no cases, others record several each month. Given this pattern, this study applies panel data regression models to identify the determinants of dengue incidence between January 2020 and June 2023. After rejecting the assumption of equidispersion (p < .05) based on the Cameron and Trivedi test, Poisson-based models were deemed unsuitable. The Zero-Inflated Negative Binomial (ZINB) model with random effects, estimated using the glmmTMB package in R, was selected as the most appropriate. Results indicate that climatic variables, particularly maximum temperature and lagged precipitation, are significant predictors of dengue incidence. Higher maximum temperatures are associated with lower incidence, whereas precipitation in the previous month slightly increases cases. In the zero-inflated component, structural variables such as access to piped water and solid waste collection increase the probability of structural zeros, indicating that improved sanitation reduces the likelihood of dengue occurrence. Although the analysis focused on Pernambuco, Brazil, the proposed modeling framework can be applied globally in similar epidemiological and climatic contexts. The findings are consistent with the existing literature and emphasize the need for integrated public policies that combine epidemiological surveillance with investments in sanitation and urban infrastructure.

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

## Key Contributions

- Application of ZINB panel data models at the state level  
- Joint analysis of climatic and structural determinants  
- Identification of structural zeros associated with sanitation coverage  
- Policy-relevant insights for dengue surveillance and prevention  

---

## Authors

- Eduardo da Silva – Federal University of Pernambuco (UFPE)  
- Maísa Mendonça Silva – Federal University of Pernambuco (UFPE)

---

## License and Availability

The data and code are made available for academic and non-commercial use.  
If you use this repository, please cite the corresponding article once published.

---

## Contact

For questions or collaborations:

eduardo.es@ufpe.br


