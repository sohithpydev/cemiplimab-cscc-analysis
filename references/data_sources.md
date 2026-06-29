# Data Sources Inventory

This document lists the public databases, clinical trials registries, and regulatory resources utilized to compile the datasets in this repository.

## 1. Protein Data Bank (RCSB PDB)
*   **Source:** [RCSB Protein Data Bank](https://www.rcsb.org)
*   **Coordinate Structures Used:**
    *   **7WVM:** Crystal structure of human PD-1 in complex with cemiplimab Fab.
    *   **8GY5:** Structural basis of human PD-1 blockade by anti-PD-1 monoclonal antibodies.
*   *Application:* Extracted resolution (Å), binding interfaces, and N58 glycosylation parameters for `data/cemiplimab_pharmacology.csv`.

## 2. ClinicalTrials.gov (NIH)
*   **Source:** [NIH ClinicalTrials.gov Registry](https://clinicaltrials.gov)
*   **Registry Identifiers:**
    *   **NCT02760498 (EMPOWER-CSCC-1):** A Phase 2 Study of Cemiplimab in Patients with Advanced Cutaneous Squamous Cell Carcinoma.
    *   **NCT03969004 (C-POST):** A Phase 3 Study of Adjuvant Cemiplimab vs. Placebo in Patients with High-Risk Resected Cutaneous Squamous Cell Carcinoma.
*   *Application:* Extracted trial cohort designs, sample sizes, and primary outcomes for `data/empower_cscc_1_efficacy.csv` and `data/c_post_efficacy.csv`.

## 3. FDA Orange Book & Purple Book
*   **Source:** [FDA Approved Drug Products Database](https://www.accessdata.fda.gov/scripts/cder/ob/index.cfm) and [Purple Book Search](https://purplebooksearch.fda.gov)
*   *Application:* Extracted regulatory licensure dates (September 2018), 12-year reference biologic data exclusivity terms, and FDA patent citations for `IP/patent_summary.csv` and `IP/exclusivity.md`.

## 4. Health Technology Assessment (HTA) Databases
*   **NICE TA578:** National Institute for Health and Care Excellence technology appraisal for cemiplimab in advanced cSCC. [NICE UK](https://www.nice.org.uk)
*   **PBS Schedule:** Australian Government Department of Health Pharmaceutical Benefits Scheme database. [PBS Australia](https://www.pbs.gov.au)
*   *Application:* Extracted national list pricing, co-payment thresholds, and HTA criteria for `financial/financial_summary.csv` and `financial/reimbursement.md`.
