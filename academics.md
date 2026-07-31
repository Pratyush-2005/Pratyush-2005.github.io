---
layout: default
title: Academics and Selected Projects
permalink: /academics/
---
[Home](/) • [Academics](/academics/) • [Readings](/readings/) • [Writings](/writings/)
---

# Featured Research & Class Spotlights

---

### Yale School of Public Health — Summer Research Internship
* **Program:** Big Data Summer Immersion at Yale 2026
* **Focus:** Electronic Health Records, Analyzing Longitudinal Data, Variable Selection, Missing Data Handling
* **Summary:** Analyzed ICU patients from MIMIC-IV data to extract features using SHAP values and Permutation importance on different machine learning models. Used Generalized Estimating Equations and OU Process modelling to check extent of association of extracted features. Used Multistage Multiple Imputation and Rubin's Rules to handle missing data and pool results.
* **Lesson Learned:** *Had to do median imputation in some predictive models due to lack of computational power. Checked only for linear forms of association.*
*  [📄 Slides (PDF)](assets/EHR Group 3.pdf)• [📄 Poster (PDF)](assets/Analyzing_Creatinine_Trajectory_with_Machine_Learning_Variable_Selection_FINAL.pdf)

---

### Longitudinal & Survival Analysis of ADPKD Progression in South Asians
* **Course:** Statistics Comprehensive Group Project, B.Stat (ISI Kolkata)
* **Focus:** Biostatistics, Survival Analysis, Mixed-Effects Growth Models, Missing Data
* **Summary:** Analyzed longitudinal clinical data (193 patients, 982 visits) from an Indian cohort presenting at advanced disease stages (41.3% CKD G5 at baseline). Combined Kaplan-Meier/Cox Proportional Hazards modeling for composite endpoints with Linear Mixed-Effects Growth Models to evaluate eGFR decline trajectories. Handled structured missingness using MICE with Predictive Mean Matching (PMM)
* **Lesson Learned:** *We should've done the imputation multiple times and then pool the results. Also the final cox model should've been applied on a pre split held out data, in the current setup the p-values are not interpretable.*
* [📄 Read Full Report (PDF)](assets/ADPKD.pdf)

---

### Bayesian Small Area Estimation of District-Level Household Consumption
* **Course:** Official Statistics Project, B.Stat (ISI Kolkata)
* **Focus:** Bayesian Hierarchical Models, Small Area Estimation (SAE), Survey Design
* **Summary:** Modeled district-level Monthly Per Capita Consumption Expenditure (MPCE) and structural urban-rural inequality across West Bengal by linking NSSO HCES microdata with Census auxiliary variables. Implemented a Unit-Level Hierarchical Bayes Model with random slopes to allow the urban premium to vary spatially across districts.
* **Lesson Learned:** *Direct survey estimates suffered from extreme variance due to small district sample sizes. There should've been some sort of diagnostic check for the model.*
* [📄 Read Full Report (PDF)](assets/Official_Statistics_Project.pdf)

---

### Comparative Demographic & Economic Analysis: Bihar vs. Kerala
* **Course:** Demography & Economic Statistics Project, B.Stat (ISI Kolkata)
* **Focus:** Complex Survey GLMs, Parity Progression, Quasi-Poisson, Modified Poisson
* **Summary:** Conducted a multi-module comparative study using NFHS-5 microdata to quantify how socioeconomic gradients vary between high-fertility (Bihar) and low-fertility (Kerala) demographic regimes across parity progression, total children ever born, sanitation, and early childbearing.
* **Lesson Learned:** *Diagnostic check available in only 1 chapter. Trying to pull too many conclusions from a small piece of data.*
* [📄 Read Full Report (PDF)](assets/Demography_and_Economic_Statistics_Project.pdf)

---

# Selected Coursework & Minor Projects

Below is a curated collection of statistical modeling, machine learning, and algorithmic implementation projects completed as part of the B.Stat curriculum at ISI Kolkata[span_16](start_span)[span_16](end_span)[span_17](start_span)[span_17](end_span)[span_18](start_span)[span_18](end_span).

---

### Synthetic Optical Character Recognition (OCR) Engine via Spatial Clustering
* **Course:** Statistical Methods II (ISI Kolkata)
* **Methods:** DBSCAN Clustering, Connected Component Labeling (CCL), Spatial Topology, Image Binarization
* **Summary:** Designed and implemented a custom OCR pipeline to recognize synthetically designed alphabets. Applied DBSCAN clustering ($\epsilon = 7.5$) on binary pixel coordinates to isolate character bounding boxes, followed by Connected Component Labeling to detect interior chambers and count binary "blobs" mapped to ASCII characters.
* **Retrospective / Lesson Learned:** *Pixel-level line gaps caused CCL to merge adjacent chambers into a single region, highlighting how topological feature extraction is highly sensitive to line continuity and image binarization thresholds. The project needed a more detailed sensitivity analysis.*
* [📄 Read Report (PDF)](assets/Statistical_Methods_2_Project_OCR.pdf)

---

### Comparative Binary Classification & Multivariate Diagnostics on Biomedical Data
* **Course:** Applied Statistics / Classification Lab (ISI Kolkata)
* **Methods:** Mahalanobis Distance K-S Test, Fisher Discriminant Analysis (FDA), QDA, Logistic Regression, Probit Regression, ROC-AUC
* **Summary:** Built a comparative classification framework on the Wisconsin Breast Cancer dataset. Evaluated multivariate normality using Kolmogorov-Smirnov tests on Mahalanobis distances ($p < 10^{-88}$) to justify non-parametric/logistic choices, and trimmed redundant variables ($r > 0.90$) to stabilize model coefficients.
* **Retrospective / Lesson Learned:** *While FDA achieved the highest AUC (0.9925), formal diagnostic testing proved that the underlying features violated multivariate normality. This reinforced the distinction between empirical classification accuracy and theoretical model assumption validity.*
* [📄 Read Report (PDF)](assets/Stat_4_Project_Report.pdf)

---

### Multiple Linear Regression & Spatial Analysis of Indian Agricultural Yields
* **Course:** Statistical Methods III (ISI Kolkata)
* **Methods:** Exploratory Data Analysis, Multiple Linear Regression (MLR), Multicollinearity Diagnostics, Residual Profiling
* **Summary:** Analyzed state-, season-, and crop-wise agricultural productivity patterns across India. Modeled rice crop production in West Bengal ($R^2 = 0.966$) using rainfall, cultivated area, and fertilizer application. Dropped pesticide usage prior to fitting due to severe collinearity with fertilizer inputs ($r = 0.95$).
* **Retrospective / Lesson Learned:** *Residual diagnostics revealed right-skewness and heteroscedasticity in raw production figures, demonstrating that macro-level agricultural yield data requires non-linear or log-transformed specifications rather than standard OLS. Also there is overfitting in the model.*
* [📄 Read Report (PDF)](assets/Stat_3_Project_Report.pdf)
* 
