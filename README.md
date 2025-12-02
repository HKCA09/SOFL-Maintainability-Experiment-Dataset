# SOFL-Maintainability-Experiment-Dataset
This repository contains the experimental datasets, materials, and analysis artifacts from our study on **quantitative maintainability assessment for SOFL formal specifications**. The dataset is directly associated with the experiments described in our paper:
> **Design and Implementation of an Automated Maintainability Assessment Tool for SOFL Formal Specifications**

---

## 🧪 Experimental Context

### Experiment I — Case Study & Usability/Effectiveness Check
- **Participants:** 21 (formal specification experts, software engineers, graduate students)
- **Setting:** Supervised in-lab sessions with a 10-minute standardized briefing; questions limited to metric-operation rules.
- **Material:** 6 SOFL modules from an ATM specification
- **Tasks:** T1–T5 tool maintenance workflows (import/inspect, run metrics, prioritize modules, visualize, export).
  1) **Import & Inspect (critical).** Load the specification and locate a target module(Manage Savings Account). 
  2) **Run Metrics & Score (critical).** Execute metrics and obtain the overall maintainability score.
  3) **Prioritize Modules (critical).** Identify modules with the lowest MHV rating and below the overall average through filtering.
  4) **Inspect the Visualization Page.** Open the visualization page and identify the module with the lowest CC value through the chart.
  5) **Export the Analysis Table.** Locate the Save Analysis Table button in the navigation bar.
- **Measures:** Success rate, time-on-task (median, IQR), errors; UMUX-Lite (0–100), UX-9 (item medians/IQR, agreement %, Cronbach’s α with bootstrap 95% CIs).

- **Technical validation:** Two independent expert annotations + third-expert adjudication to form an expert-consensus reference; agreement quantified via ICC(2,k); tool-to-consensus via ICC(2,1), Bland–Altman bias and 95% limits of agreement, MdAE, MAPE.
 Material: 6 modules from one SOFL ATM specification (printed text to standardize environment).

### Experiment II — Validation of Metrics & Rating Methodology
- **Participants:** 20 total; partial overlap with Experiment I (8 individuals). Newly recruited participants include faculty, engineers, product/operations staff, and graduate students.
- **Setting:** Remote, unsupervised with standardized briefing; clarifications restricted to metric rules.
- **Material:** **30 modules** from **6 SOFL specifications**  
  *ATM SYSTEM, COURSE_REGISTRATION, HOSPITAL_REGISTRATION, PUBLIC_TRANSPORT_TICKETING, STOCK_TRADING, VENDING_MACHINE*
  Each participant rated 3 randomly assigned modules; every module received ≥2 independent ratings.
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
