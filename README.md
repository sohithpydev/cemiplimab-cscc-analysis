# Comprehensive Analysis of Cemiplimab (Libtayo®) for Advanced & Adjuvant cSCC

Welcome to the open-source pharmaceutical intelligence and computational biology repository for **Cemiplimab (Libtayo®)** in the treatment of Cutaneous Squamous Cell Carcinoma (cSCC).

This project integrates clinical oncology evidence, structural molecular biology, pharmacology, regulatory history, and safety data to provide a publication-quality analysis of cemiplimab. All data and figures are generated programmatically and are fully reproducible.

---

## 🔬 Key Research Components

### 1. Mechanism of Action (MoA) & Pharmacology
*   **Target:** Selective blocking of the Programmed Cell Death Protein 1 (PD-1) pathway on T-cells.
*   **Binding Kinetics:** High affinity binding ($K_D \approx 0.60$ nM) with dependency on PD-1 N58 glycosylation.
*   **Molecular Structures:** Structural analyses are documented using PDB coordinate structures [7WVM](https://www.rcsb.org/structure/7WVM) and [8GY5](https://www.rcsb.org/structure/8GY5).
*   **Pharmacokinetics:** Elimination half-life of 20–22 days at steady state, supporting Q3W or Q2W dosing.
*   See [cemiplimab_pharmacology.csv](file:///Users/sohith/Desktop/cemiplimab/data/cemiplimab_pharmacology.csv) for structured parameters.

### 2. Clinical Trial Efficacy
*   **Advanced cSCC (EMPOWER-CSCC-1 / NCT02760498):**
    *   Pooled Objective Response Rate (ORR) of **47.2%** (n=193) with a **16.1%** Complete Response (CR) rate.
    *   Median Progression-Free Survival (PFS) of **26.0 months**.
    *   See [empower_cscc_1_efficacy.csv](file:///Users/sohith/Desktop/cemiplimab/data/empower_cscc_1_efficacy.csv) for cohort breakdowns.
*   **Adjuvant Setting (C-POST / NCT03969004):**
    *   **68% reduction** in the risk of disease recurrence or death (Hazard Ratio = **0.32** [95% CI: 0.20 - 0.51], $P < 0.0001$).
    *   12-Month Disease-Free Survival (DFS) rate of **92.4%** vs 69.5% for placebo.
    *   See [c_post_efficacy.csv](file:///Users/sohith/Desktop/cemiplimab/data/c_post_efficacy.csv) for comparison tables.

### 3. Clinical Development & Subgroup Analysis
*   **Consistent Subgroup Efficacy:** Efficacy is maintained in elderly populations, which is vital given the demographics of skin cancer. ORR is **44.9%** in patients $\ge$ 75 years, compared to **53.0%** in patients 65–75, and **42.9%** in patients <65.
*   **ECOG Status:** Efficacy remains high in both ECOG PS 0 (**48.4%**) and ECOG PS 1 (**46.1%**) patients.
*   See [empower_cscc_1_subgroups.csv](file:///Users/sohith/Desktop/cemiplimab/data/empower_cscc_1_subgroups.csv) for complete subgroup data.

### 4. Safety Profile & Tolerability
*   **Tolerability:** Cemiplimab is well-tolerated, with a discontinuation rate due to toxicities of **9.8%** in the adjuvant setting.
*   **Common Toxicities:** Low rates of severe Grade 3–4 adverse events (e.g., Fatigue 1.2% in adjuvant cemiplimab vs 0.5% in placebo).
*   **Immune-Related AEs (irAEs):** Endocrine toxicities like Hypothyroidism occur in 10% of adjuvant patients.
*   See [cemiplimab_safety_ae_profile.csv](file:///Users/sohith/Desktop/cemiplimab/data/cemiplimab_safety_ae_profile.csv) for full AE details.

### 5. Regulatory Evolution & History
*   **Approved Indications:** Approvals span advanced cSCC (2018), advanced Basal Cell Carcinoma (2021), advanced NSCLC (2021/2022), and adjuvant high-risk cSCC (2025).
*   **Regulatory Programs:** Leveraged FDA's breakthrough therapy status, priority review, and the Real-Time Oncology Review (RTOR) pilot program.
*   See [cemiplimab_regulatory_history.csv](file:///Users/sohith/Desktop/cemiplimab/data/cemiplimab_regulatory_history.csv) for the timeline.

---

## 📁 Repository Structure

*   📂 [data/](file:///Users/sohith/Desktop/cemiplimab/data) — Structured CSV files containing curated trial data.
    *   [empower_cscc_1_efficacy.csv](file:///Users/sohith/Desktop/cemiplimab/data/empower_cscc_1_efficacy.csv)
    *   [c_post_efficacy.csv](file:///Users/sohith/Desktop/cemiplimab/data/c_post_efficacy.csv)
    *   [cemiplimab_pharmacology.csv](file:///Users/sohith/Desktop/cemiplimab/data/cemiplimab_pharmacology.csv)
    *   [cemiplimab_regulatory_history.csv](file:///Users/sohith/Desktop/cemiplimab/data/cemiplimab_regulatory_history.csv)
    *   [empower_cscc_1_subgroups.csv](file:///Users/sohith/Desktop/cemiplimab/data/empower_cscc_1_subgroups.csv)
    *   [cemiplimab_safety_ae_profile.csv](file:///Users/sohith/Desktop/cemiplimab/data/cemiplimab_safety_ae_profile.csv)
*   📂 [notebooks/](file:///Users/sohith/Desktop/cemiplimab/notebooks) — Executable Jupyter Notebooks for analysis.
    *   [01_clinical_efficacy.ipynb](file:///Users/sohith/Desktop/cemiplimab/notebooks/01_clinical_efficacy.ipynb) — Efficacy analysis and KM curves.
    *   [02_regulatory_safety.ipynb](file:///Users/sohith/Desktop/cemiplimab/notebooks/02_regulatory_safety.ipynb) — Subgroups, safety, and timeline plots.
*   📂 [docs/](file:///Users/sohith/Desktop/cemiplimab/docs) — Scientific summaries.
    *   [01_mechanism_and_efficacy.md](file:///Users/sohith/Desktop/cemiplimab/docs/01_mechanism_and_efficacy.md) — MoA and clinical trial review.
    *   [02_regulatory_and_safety.md](file:///Users/sohith/Desktop/cemiplimab/docs/02_regulatory_and_safety.md) — Subgroup efficacy, AEs, and regulatory details.
*   📂 [figures/](file:///Users/sohith/Desktop/cemiplimab/figures) — Exported publication-quality figures.
    *   [empower_cscc_1_efficacy.png](file:///Users/sohith/Desktop/cemiplimab/figures/empower_cscc_1_efficacy.png)
    *   [c_post_dfs_efficacy.png](file:///Users/sohith/Desktop/cemiplimab/figures/c_post_dfs_efficacy.png)
    *   [c_post_hazard_ratio.png](file:///Users/sohith/Desktop/cemiplimab/figures/c_post_hazard_ratio.png)
    *   [cemiplimab_regulatory_timeline.png](file:///Users/sohith/Desktop/cemiplimab/figures/cemiplimab_regulatory_timeline.png)
    *   [empower_subgroups_efficacy.png](file:///Users/sohith/Desktop/cemiplimab/figures/empower_subgroups_efficacy.png)
    *   [cemiplimab_safety_comparison.png](file:///Users/sohith/Desktop/cemiplimab/figures/cemiplimab_safety_comparison.png)

---

## 📈 Visualizations Showcase

### EMPOWER-CSCC-1 Response Rates & Subgroups
![EMPOWER-CSCC-1 Efficacy](figures/empower_cscc_1_efficacy.png)
![EMPOWER-CSCC-1 Subgroups](figures/empower_subgroups_efficacy.png)

### C-POST Adjuvant DFS Rates & Hazard Ratio
![C-POST DFS](figures/c_post_dfs_efficacy.png)
![C-POST Hazard Ratio](figures/c_post_hazard_ratio.png)

### C-POST Adjuvant Safety Profile (vs Placebo)
![C-POST Safety](figures/cemiplimab_safety_comparison.png)

### Indication Approval Evolution Timeline
![Regulatory Timeline](figures/cemiplimab_regulatory_timeline.png)

---

## 🔬 How to Run the Analyses

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/cemiplimab.git
    cd cemiplimab
    ```
2.  **Install dependencies:**
    Ensure you have Python 3, Pandas, Matplotlib, and Seaborn installed.
    ```bash
    pip install pandas matplotlib seaborn jupyter
    ```
3.  **Run the notebooks:**
    ```bash
    jupyter notebook notebooks/01_clinical_efficacy.ipynb
    jupyter notebook notebooks/02_regulatory_safety.ipynb
    ```

---

## 📑 Core Principles
This repository strictly operates under open-source data standards. No patient-level protected information is utilized. All conclusions are drawn from peer-reviewed clinical publications and regulatory documents (FDA, EMA).

For a detailed roadmap of this project, please consult the workspace task tracker [TASKS.md](file:///Users/sohith/Desktop/cemiplimab/TASKS.md).