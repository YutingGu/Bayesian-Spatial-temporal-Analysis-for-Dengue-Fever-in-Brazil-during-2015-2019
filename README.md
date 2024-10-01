# Bayesian Spatial-Temporal Analysis of Dengue Fever in Brazil (2015-2019)

### Overview
This project is an individual submission for the Advanced Analysis course. It involves an ecological study focusing on the spatial-temporal dynamics of dengue fever in Brazil from 2015 to 2019. Using a Bayesian hierarchical model, this analysis aims to explore the relationships between climatic variables—such as monthly maximum temperature and Palmer’s drought severity index (PDSI)—and dengue incidence across 557 microregions over 60 months. The results contribute to understanding the patterns of dengue transmission and can aid in informing public health interventions.

### Key Features
- **Study Objective:** Investigate the spatial and temporal patterns of dengue fever and its association with climatic factors.
- **Data Sources:** Dengue case data from Brazil's Notifiable Diseases Information System (DATASUS) and climatic data from the Climatic Research Unit. Dataset used can be found in [here](DS3_DengueBrazil).
- **Modelling Approach:** Utilised Bayesian hierarchical models and spatial generalised linear mixed-effect models (GLMM) with type I interaction to predict dengue incidence.

### Methodology
Five models were developed to analyse the data, with a focus on spatial and spatial-temporal variations. The spatial-temporal models incorporated climatic covariates to predict dengue fever incidence, with particular attention to regions at high risk. Results were compared based on model fit using the Watanabe–Akaike information criterion (WAIC).

### Findings
- High-risk regions were primarily located in Southeast and Centre-West Brazil.
- A periodic outbreak pattern was observed, though no clear yearly trend emerged.
- The model with spatial-temporal interactions and covariates provided the most accurate predictions for dengue cases.

### Conclusion
This analysis offers insights into the climatic drivers of dengue fever and highlights the importance of targeted interventions in high-risk areas. While the inclusion of covariates provided meaningful results, future studies could explore more complex interactions to enhance predictive accuracy.


### Code
The relevant code for the analysis can be found in [this RMarkdown file](Analysis_Script.Rmd).

### Analysis Report
Full analysis report can be found in [here](Analysis_Report.pdf).
