# Project Summary: Cemiplimab (Libtayo®) cSCC Research Repository

## 1. Executive Summary
This project has successfully created a comprehensive, publication-quality research repository dedicated to **Cemiplimab (Libtayo®)** for Cutaneous Squamous Cell Carcinoma (cSCC). Integrating evidence across structural biology, randomized clinical trials, precision biomarkers, intellectual property, commercial landscape, financials, and post-market real-world outcomes, this resource provides a multidisciplinary review of the first approved immunotherapy in advanced and adjuvant cSCC.

All analyses are fully reproducible, backed by curated datasets (CSVs) and Jupyter Notebooks (IPYNBs), generating 12 publication-quality figures exported to the `figures/` directory.

---

## 2. Repository Statistics

| Asset Type | Count | Key Contents |
| :--- | :---: | :--- |
| **Datasets (CSVs)** | **11** | Pharmacology, clinical trial efficacy (EMPOWER-CSCC-1, C-POST), safety, regulatory history, biomarker summary, patent database, commercial datasets, financial parameters, and real-world evidence registries. |
| **Jupyter Notebooks** | **7** | Efficacy, safety & subgroups, biomarkers, patent timeline, commercial growth, financial price-normalization, and real-world evidence analysis. |
| **Figures (PNGs)** | **12** | Efficacy bar plots, safety comparisons, TMB boxplots, biomarker heatmaps, patent Gantt timelines, revenue growth, geographic pricing, and real-world benchmarks. |
| **Markdown Documents** | **40** | MoA reviews, clinical papers, biomarker studies, patent landscapes, biosimilar reports, commercial plans, guideline summaries, pricing analyses, HTA decisions, health economics reports, RWE summaries, bibliographies, project manuals, and technical blog posts. |

---

## 3. Directory Inventory

*   📂 `data/` — 6 clinical/pharmacological CSV datasets.
*   📂 `notebooks/` — 2 notebooks analyzing trial efficacy, subgroups, and safety.
*   📂 `docs/` — Clinical reviews, project manual, glossary, figure index, and data dictionary.
*   📂 `biomarker/` — Biomarker reports, catalog, and heatmap/TMB analysis notebook.
*   📂 `IP/` — Patent databases, regulatory exclusivity Gantt charts, and biosimilar reports.
*   📂 `commercial/` — Commercial summaries, competitor datasets, guidelines, and revenue analysis notebook.
*   📂 `financial/` — Pricing databases, currency normalization notebooks, reimbursement documents, and health economics reviews.
*   📂 `post_launch/` — RWE databases, safety registries, guideline updates, and future clinical directions.
*   📂 `references/` — BibTeX bibliography files, references, and public data source inventories.
*   📂 `blog/` — 7 technical articles reviewing each research phase.
*   📂 `figures/` — 12 programmatically generated plots.
*   📂 `.github/workflows/` — CI/CD YAML configuration for verification.

---

## 4. Scientific Findings & Key Metrics
1.  **High Affinity Glyco-Epitope:** Cemiplimab binds human PD-1 IgV with $K_D \approx 0.60$ nM, dependent on the N58 glycosylation site (PDB 7WVM/8GY5).
2.  **Robust Efficacy:** Pooled ORR of **47.2%** (16.1% CR) in advanced disease, and **68% recurrence risk reduction** (HR=0.32) in adjuvant setting.
3.  **TMB Response Marker:** cSCC has one of the highest TMBs (~50 mut/Mb median) due to Signature 7 (UV). Responders exhibit significantly higher TMB (53–61 mut/Mb) vs non-responders (13–19 mut/Mb).
4.  **IP Layering:** Core composition patents expire in **2035**, with method-of-use/formulation patents extending protection to **2037–2038**. Regulatory exclusivity extends to **2030 (US)** and **2029 (EU)**.
5.  **Blockbuster Performance:** YoY growth of **40.1%** in global sales, reaching **$1.217 billion** in 2024.
6.  **Cost-Effectiveness:** ICER of **$99,024 per QALY gained** vs. chemotherapy in the US, well within standard WTP thresholds.
7.  **Real-world Concordance:** Registries (CASE, REACT-CEMI) confirm trial ORR (~42-44%) and establish real-world median OS at **21–25 months**.
8.  **Future Neoadjuvant Role:** High pCR rate of **50.6%** (Gross 2022 NEJM) enables organ-sparing surgical resections in Stage II-IV resectable cSCC.

---

## 5. Limitations & Future Work
*   **Data Resolution:** Clinical datasets are compiled from aggregated trial results. Future work could incorporate patient-level synthetic datasets to model survival curves (Kaplan-Meier) dynamically.
*   **Pharmacokinetic Simulations:** While ADME parameters are documented, implementing full PK/PD differential equation models (in Python/scipy) representing cemiplimab Q3W clearancemodels represents an opportunity for Phase 8.
*   **Resistance Biology:** Expanding research into tumor single-cell RNA sequencing to map T-cell exhaustion transcripts prior to combination therapy initiation.
