# Repository Data Dictionary

This document serves as the data dictionary, defining the schema and column definitions for all curated CSV datasets in the repository.

---

## 1. Pharmacology Data
*   **File Path:** `data/cemiplimab_pharmacology.csv`
*   **Description:** Molecular kinetics, structural parameters, and ADME profile for cemiplimab.
*   **Columns:**
    *   `parameter_name` (Text): Name of the pharmacological variable (e.g., Kd, Binding Epitope, Half-Life).
    *   `value` (Text/Numeric): Value or description of the parameter.
    *   `unit` (Text): Unit of measurement (e.g., nM, days, Å).
    *   `reference` (Text): Source citation.

---

## 2. Clinical Trial Efficacy
*   **File Path:** `data/empower_cscc_1_efficacy.csv` & `data/c_post_efficacy.csv`
*   **Description:** Efficacy outcomes (ORR, CR, DFS, PFS) for advanced and adjuvant trials.
*   **Columns:**
    *   `cohort` (Text): Patient group details (e.g., Metastatic Q2W, Locally Advanced Q3W).
    *   `sample_size` (Integer): Number of evaluable patients.
    *   `orr` (Float): Objective Response Rate (%).
    *   `cr` (Float): Complete Response Rate (%).
    *   `pfs_median` (Float): Median Progression-Free Survival (months).
    *   `hazard_ratio` (Float): Risk reduction metric (for C-POST).

---

## 3. Subgroup Efficacy
*   **File Path:** `data/empower_cscc_1_subgroups.csv`
*   **Description:** ORR breakdowns across key patient demographics (Age, ECOG PS, Disease setting).
*   **Columns:**
    *   `subgroup_category` (Text): Demographic classification (e.g., Age, ECOG Status).
    *   `subgroup_level` (Text): Specific range (e.g., >= 75 years, ECOG 1).
    *   `sample_size` (Integer): Patient count.
    *   `orr` (Float): Objective Response Rate (%).

---

## 4. Safety Profile
*   **File Path:** `data/cemiplimab_safety_ae_profile.csv`
*   **Description:** Percentages of common and severe adverse events in cemiplimab vs placebo.
*   **Columns:**
    *   `adverse_event` (Text): Name of the toxicity (e.g., Fatigue, Pruritus, Hypothyroidism).
    *   `grade_level` (Text): Severity classification (All Grades vs. Grade 3-4).
    *   `cemiplimab_pct` (Float): Occurrence rate in cemiplimab cohort (%).
    *   `placebo_pct` (Float): Occurrence rate in placebo cohort (%).

---

## 5. Exclusivity & Patent Database
*   **File Path:** `IP/patent_summary.csv`
*   **Description:** Global patent entries (US, EP, JP) and legal status.
*   **Columns:**
    *   `patent_number` (Text): Official patent identifier (e.g., US 9,987,500).
    *   `patent_title` (Text): Official registered title.
    *   `jurisdiction` (Text): Region (US, EP, JP).
    *   `filing_date` (Date): YYYY-MM-DD.
    *   `expiration_date` (Date): YYYY-MM-DD.
    *   `assignee` (Text): Owner (Regeneron Pharmaceuticals).
    *   `technology_category` (Text): Classification (Composition, Method of Use, Formulation).

---

## 6. Financial Summary
*   **File Path:** `financial/financial_summary.csv`
*   **Description:** Country pricing, national revenues, and cost-effectiveness benchmarks.
*   **Columns:**
    *   `parameter_type` (Text): Classification (Pricing, Revenue, Market Size).
    *   `region` (Text): Geographic scope (US, UK, Japan, Australia, Global).
    *   `metric` (Text): Specific variable measured (e.g., WAC price, annual sales).
    *   `value` (Float): Numeric value.
    *   `currency` (Text): Currency identifier (USD, GBP, AUD, JPY).
    *   `fiscal_year` (Integer): Year of reporting.
