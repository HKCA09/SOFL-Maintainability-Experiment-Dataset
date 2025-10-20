# SOFL-Maintainability-Experiment-Dataset
This repository contains the experimental datasets, materials, and analysis artifacts from our study on **quantitative maintainability assessment for SOFL formal specifications**. The dataset is directly associated with the experiments described in our paper:
> **Design and Implementation of an Automated Maintainability Assessment Tool for SOFL Formal Specifications**

---

## 🧪 Experimental Context

### Experiment I — Case Study & Usability/Effectiveness Check
- **Participants:** 21 (formal specification experts, software engineers, graduate students)
- **Material:** 6 SOFL modules from an ATM specification
- **Goals:**  
  1) Compare **tool-computed metrics** with **expert-averaged assessments**  
  2) Collect usability feedback  
- **Outcomes:** Preliminary consistency analysis (Pearson’s *r*) and qualitative remarks

### Experiment II — Validation of Metrics & Rating Methodology
- **Participants:** 20 (researchers/practitioners and graduate students with SOFL/formal methods background)
- **Material:** **30 modules** from **6 SOFL specifications**  
  *ATM SYSTEM, COURSE_REGISTRATION, HOSPITAL_REGISTRATION, PUBLIC_TRANSPORT_TICKETING, STOCK_TRADING, VENDING_MACHINE*
- **Tasks:**  
  1) **Metric Quality:** Clarity, Relevance, Rationality, Coverage (5-point Likert)  
  2) **Human Validation:** Agreement with overall and per-metric tool ratings (5-point Likert)  
  3) **Importance Ranking:** Total order over 8 metrics (no ties)

Full methodology and analysis are described in the associated paper.

## 🛠Supporting Tool — SOFL-ASMAT
**SOFL-ASMAT** parses SOFL specifications and produces maintainability profiles using **eight structured metrics** and **hierarchical rating rules** :
- **Metrics:** LOE, NOP, NOCDF, CC, MHV, NODSU, EOC, EOBL  
- **Ratings:** Standardized scores and categorical bands (A–D)

> Tool quickstart is provided in `/SOFL-AutomatedSoftwareMaintainabilityAssessmentTool/`.

## 📜 License
This dataset is licensed under the [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License (CC BY-NC-ND 4.0)](https://creativecommons.org/licenses/by-nc-nd/4.0/).

You are free to:
- Share — copy and redistribute the material in any medium or format.

Under the following terms:
- **Attribution** — You must give appropriate credit.
- **NonCommercial** — You may not use the material for commercial purposes.
- **NoDerivatives** — If you remix, transform, or build upon the material, you may not distribute the modified material.

Full license text is available in the LICENSE file.
