---
title: Using a surrogate-assisted Bayesian framework to calibrate the runoff-generation
  scheme in the Energy Exascale Earth System Model (E3SM) v1
authors:
- admin
- G. Bisht
- K. Sargsyan
- C. Liao
- L. R. Leung
date: '2022-07-01'
publishDate: '2025-05-02T05:27:35.152934Z'
publication_types:
- article-journal
publication: '*Geoscientific Model Development*'
doi: 10.5194/gmd-15-5021-2022
abstract: Runoff is a critical component of the terrestrial water cycle, and Earth system models (ESMs) are essential tools to study its spatiotemporal variability. Runoff schemes in ESMs typically include many parameters so that model calibration is necessary to improve the accuracy of simulated runoff. However, runoff calibration at a global scale is challenging because of the high computational cost and the lack of reliable observational datasets. In this study, we calibrated 11 runoff relevant parameters in the Energy Exascale Earth System Model (E3SM) Land Model (ELM) using a surrogate-assisted Bayesian framework. First, the polynomial chaos expansion machinery with Bayesian compressed sensing is used to construct computationally inexpensive surrogate models for ELM-simulated runoff at 0.5∘ × 0.5∘ for 1991–2010. The error metric between the ELM simulations and the benchmark data is selected to construct the surrogates, which facilitates efficient calibration and avoids the more conventional, but challenging, construction of high-dimensional surrogates for the ELM simulated runoff. Second, the Sobol' index sensitivity analysis is performed using the surrogate models to identify the most sensitive parameters, and our results show that, in most regions, ELM-simulated runoff is strongly sensitive to 3 of the 11 uncertain parameters. Third, a Bayesian method is used to infer the optimal values of the most sensitive parameters using an observation-based global runoff dataset as the benchmark. Our results show that model performance is significantly improved with the inferred parameter values. Although the parametric uncertainty of simulated runoff is reduced after the parameter inference, it remains comparable to the multimodel ensemble uncertainty represented by the global hydrological models in ISMIP2a. Additionally, the annual global runoff trend during the simulation period is not well constrained by the inferred parameter values, suggesting the importance of including parametric uncertainty in future runoff projections.
# Summary. An optional shortened abstract.
summary: The runoff outputs in Earth system model simulations involve high uncertainty, which needs to be constrained by parameter calibration. In this work, we used a surrogate-assisted Bayesian framework to efficiently calibrate the runoff-generation processes in the Energy Exascale Earth System Model v1 at a global scale. The model performance was improved compared to the default parameter after calibration, and the associated parametric uncertainty was significantly constrained.
tags:
- Earth System Model
featured: true
links:
- name: URL
  url: https://gmd.copernicus.org/articles/15/5021/2022/
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false
# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- Integrated Coastal Modeling (https://icom.pnnl.gov/)
---


