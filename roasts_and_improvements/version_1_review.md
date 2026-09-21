# GitHub Profile Audit & Action Plan — Version 1 Review

**Target Account:** [@val-jerono](https://github.com/VAL-Jerono)  
**Profile Owner:** Valerie Jerono — Data Scientist & ML Risk Engineer  
**Date of Review:** September 21, 2026  
**Baseline Score:** **41.50 / 100** (`NPC` — Average · Unremarkable)  
**Current Rank:** #2,959 of 7,298 developers audited (Beat 59.3%)  
**Target Threshold:** **70.00+** (`SOLID` Tier — Requires +28.50 pts)  

---

## 📊 Scorecard & Benchmark Summary

| Dimension | Current Score | Max Score | Status / Diagnostic |
| :--- | :---: | :---: | :--- |
| **Account Maturity** | **6.6** | 10.0 | Account age ~3.08 yrs; output quality doesn't match account tenure. |
| **Original Project Quality** | **6.0** | 18.0 | 73 original repos, 0 total stars; top repo (`a2-models`) rated 1/10 due to course assignment framing. |
| **Contribution Quality** | **12.6** | 27.0 | 8 merged PRs, all self-hosted; 0 external contributions or maintainer interactions. |
| **Ecosystem / Maintenance Impact** | **0.0** | 20.0 | **Critical Failure (0/20)** — Zero commits or PRs into external/popular open-source repos. |
| **Community Influence** | **2.6** | 8.0 | 4 followers vs. 5 following — negative ratio, zero star accumulation. |
| **Activity Authenticity** | **13.7** | 17.0 | **Strong Baseline** — 723 annual contributions; activity is real but self-isolated. |
| **TOTAL SCORE** | **41.50** | **100.0** | **NPC Tier** — Self-contained activity with zero external validation. |

---

## 🔥 Full Roast & Unfiltered Findings Record

> **Verdict:** *A zero-star presence farm with 99 self-repos, no external impact, and fewer followers than accounts you follow — your GitHub profile is just a fancy open-source business card.*

### Audit Highlights & Evidence:
1. **Repository Bloat vs. Zero Star Conversion:** 99 self-hosted repositories with an aggregate total of 0 stars across the entire profile.
2. **Academic Framing Penalty:** High-quality code pipelines (such as `a2-models` with 1,088 lines of clean Python, Bayesian Optuna tuning, SHAP explainability, and CBK regulatory compliance) are hidden under student course assignment tags like "DSA 8401".
3. **Ecosystem Isolation:** 723 yearly contributions, but 100% of commits and PRs are internal. Zero footprint on external open-source projects.
4. **Language Breakdown:**
   - Jupyter Notebook: **68%**
   - Python: **12%**
   - HTML: **8%**
   - JavaScript: **3%**
   - TypeScript: **3%**
   - PHP: **2%**

---

## 🚨 Root Cause Analysis of Downsides

```
                          ┌──────────────────────────────────────────────┐
                          │    Profile Bottlenecks (Score: 41.50/100)    │
                          └──────────────────────┬───────────────────────┘
                                                 │
      ┌──────────────────────┬───────────────────┼───────────────────┬──────────────────────┐
      │                      │                   │                   │                      │
┌─────┴──────────────┐ ┌─────┴────────────┐ ┌────┴──────────────┐ ┌──┴──────────────┐ ┌─────┴──────────────┐
│  Ecosystem Isolation│ │ Academic Framing│ │ Portfolio Bloat   │ │ Zero Social Proof│ │ Notebook Heavy     │
│   (Score: 0.0/20)  │ │  (Score: 6.0/18) │ │ (99 Uncurated)    │ │ (0 Stars, 4 Foll)│ │ (68% .ipynb Ratio) │
└────────────────────┘ └─────────────────┘ └───────────────────┘ └──────────────────┘ └────────────────────┘
```

1. **Ecosystem Vacuum (0/20):** You are coding in a silo. GitHub rewards developers who contribute to the broader ecosystem. Zero external PRs cap your score ceiling.
2. **Packaging & Naming Issue:** Repos like `a2-models`, `Applied_Machine_Learning`, and `Credit-Risk_Data-Preprocessing` sound like homework submissions. Recruiters and algorithms bypass them.
3. **Quantity Over Curation:** Having ~99 self-repos with basic notebooks dilutes your best work. The algorithm sees 73 original repos with 0 stars and classifies the profile as a "presence farm".
4. **Hidden Engineering Excellence:** Your underlying technical work in `a2-models` (cost-aware loss function, SMOTE temporal leakage proof, probability calibration) is senior-level, but its presentation conceals its value.

---

## 🎯 Strategic Action Plan & Improvement Regions

### Region 1: Portfolio Cleanup & Naming Transformation
*Goal: Convert academic names into industry-grade product titles and curate profile visibility.*

- [ ] **Rename Key Repositories:**
  - `a2-models` ➔ `mobile-money-fraud-detection` (or `credit-risk-ml-framework`)
  - `Credit-Risk_Data-Preprocessing` ➔ `credit-risk-pipeline`
  - `CRD-TB_Patient_Cost_Study` ➔ `tb-patient-cost-analytics`
  - `Applied_Machine_Learning` ➔ `machine-learning-case-studies`
- [ ] **Repo Curation:**
  - Archive (or make private) low-value, duplicate, or raw homework repos.
  - Target: Reduce visible public repos from ~99 down to ~15-20 high-quality projects.
- [ ] **Profile Pinning:** Pin top 6 curated repositories with clear descriptions and topic tags (`python`, `machine-learning`, `fraud-detection`, `lightgbm`, `optuna`, `fintech`).

---

### Region 2: README & Documentation Engineering
*Goal: Turn repository READMEs into executive-level, production-ready product pages.*

- [ ] **Strip Academic Markers:** Remove course codes (e.g., "DSA 8401", student IDs, assignment headers) from all READMEs and code headers.
- [ ] **Upgrade `mobile-money-fraud-detection` (a2-models) README:**
  - Add shield badges (Python version, license, LightGBM, Optuna, build status).
  - Include an **Executive Summary** highlighting business impact (e.g., "Saves KES 7.3M per 31k txns via calibrated decision thresholds").
  - Add a **60-Second Quickstart** snippet so anyone can clone and run `python a2_pipeline.py`.
  - Embed high-resolution visual charts (`images/3_reliability_diagram.png`, `images/5_cost_comparison.png`).
  - Add a **Regulatory Compliance** section (CBK Digital Credit Providers Regulations 2022).

---

### Region 3: Ecosystem & Open Source Contribution (0/20 ➔ 15+/20)
*Goal: Gain external validation by making meaningful open-source contributions.*

- [ ] **Target Open-Source Libraries (1 PR per month minimum):**
  - **[Optuna](https://github.com/optuna/optuna):** Docstring fixes, example notebook additions, or issue triage.
  - **[imbalanced-learn](https://github.com/scikit-learn-contrib/imbalanced-learn):** Documentation updates, tutorial contributions on temporal leakage prevention.
  - **[scikit-learn](https://github.com/scikit-learn/scikit-learn):** Target `good first issue` / documentation improvements.
  - **[pandas](https://github.com/pandas-dev/pandas):** Type hint fixes, documentation enhancements.
- [ ] **Local/Regional Ecosystem:** Contribute to African data & tech community repositories (e.g., Kenya Data Science, open-data initiatives).

---

### Region 4: Technical Content Distribution & Star Acquisition
*Goal: Turn technical insights into stars, followers, and industry authority.*

- [ ] **Publish Technical Article 1:** Write a technical post titled *"Why SMOTE Pre-Splitting Inflates Fraud Detection Metrics by 137% (and How to Fix It)"* using data from your leakage experiment.
  - Platform: Medium / Towards Data Science / LinkedIn Articles.
  - Link directly back to your GitHub repo.
- [ ] **Share on Developer Platforms:**
  - Reddit: r/MachineLearning, r/learnmachinelearning, r/Python.
  - Kaggle Discussions / Show HN (Hacker News).
- [ ] **Profile SEO & Bio:**
  - Set GitHub Bio: *"Data Scientist & ML Risk Engineer | Credit Risk, Fraud Detection & Cost-Aware ML Systems | Python · LightGBM · Optuna · SQL"*
  - Add Location: Nairobi, Kenya.
  - Link LinkedIn profile and personal website/portfolio.

---

### Region 5: Technical Niche Brand Positioning
*Goal: Position profile as the authority on East African Fintech ML & Regulatory Risk Engineering.*

- [ ] Focus featured projects on **Mobile Money (M-Pesa format) Fraud Analytics**, **CBK Compliance Frameworks**, and **African Healthcare Cost Modeling**.
- [ ] Build a modular Python package (e.g., `cost-aware-ml` or `fintech-risk-toolkit`) and publish it on PyPI.

---

## 📈 Roadmap & Target Milestone Matrix

```
       Current V1 (41.50)           Milestone V2 (55.00)          Target V3 (70.00+ SOLID)
   ┌────────────────────────┐    ┌────────────────────────┐    ┌────────────────────────┐
   │ • 0/20 Ecosystem       │    │ • 5/20 Ecosystem       │    │ • 15/20 Ecosystem      │
   │ • 6/18 Project Quality │ ──>│ • 11/18 Project Qual  │ ──>│ • 16/18 Project Qual  │
   │ • 2.6/8 Influence      │    │ • 4.5/8 Influence      │    │ • 6.5/8 Influence      │
   │ • 0 Stars / 4 Foll     │    │ • 25+ Stars / 20+ Foll │    │ • 100+ Stars / 50+ Foll│
   └────────────────────────┘    └────────────────────────┘    └────────────────────────┘
```

---

## 📝 Review Log & Progress Tracker

| Review Version | Date | Score | Key Milestone Achieved | Notes |
| :---: | :---: | :---: | :--- | :--- |
| **v1.0** | 2026-09-21 | **41.50** | Baseline Audit Recorded | Initial roast documented; action plan formulated. |
| **v1.1** | *Pending* | — | Repo Rename & README Overhaul | Pending execution. |
| **v1.2** | *Pending* | — | First External PR Merged | Target: +10 pts on Ecosystem. |
| **v2.0** | *Pending* | — | 70+ Score Target | Re-run profile roaster evaluation. |

---

*Document maintained inside `VAL-Jerono/roasts_and_improvements/version_1_review.md`.*
