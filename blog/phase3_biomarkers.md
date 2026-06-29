# Phase 3: Biomarkers & Precision Medicine in cemiplimab cSCC therapy

## Introduction
Precision oncology relies on biomarkers to select patients and predict response to immunotherapy. However, cutaneous squamous cell carcinoma (cSCC) exhibits a unique biomarker landscape. In this post, we analyze PD-L1 expression, Tumor Mutational Burden (TMB), and the tumor immune microenvironment (TIME) in cemiplimab response.

---

## 1. PD-L1 Expression: Not a Gatekeeper
In many solid tumors (such as NSCLC), PD-1 inhibitors are restricted to patients with high PD-L1 expression.
*   **The Findings:** In cSCC clinical trials, responses to cemiplimab occur in both PD-L1-positive and PD-L1-negative tumors.
*   **The Reason:** cSCC is characterized by high baseline inflammation and immune infiltration, which allows the immune system to respond to PD-1 blockade even when baseline PD-L1 staining is low. PD-L1 expression is therefore not a mandatory selection biomarker.

---

## 2. Tumor Mutational Burden (TMB) and Signature 7
*   **High Mutation Count:** cSCC has one of the highest TMBs (~50 mut/Mb median) among all solid tumors.
*   **UV Signature:** This high TMB is driven by exposure to ultraviolet (UV) radiation, which creates a distinct **Signature 7 mutation pattern** (C>T transitions at dipyrimidine sites).
*   **Correlation with Response:** High TMB correlates with clinical benefit. In EMPOWER-CSCC-1, responders exhibited a median TMB of **53–61 mut/Mb**, compared to **13–19 mut/Mb** in non-responders. High TMB leads to a high density of novel neoantigens, rendering the tumor highly immunogenic.

---

## 3. Mechanisms of Primary and Acquired Resistance
Despite cSCC's immunogenicity, approximately 50% of patients do not respond to cemiplimab (primary resistance) or eventually progress (acquired resistance):
*   **MHC Class I Loss:** Loss-of-function mutations in **Beta2-Microglobulin (B2M)** prevent the cell-surface presentation of tumor antigens, allowing cells to hide from CD8+ T-cells.
*   **JAK1/JAK2 Mutations:** Mutations in the JAK/STAT signaling pathway render tumor cells insensitive to interferon-gamma (IFN-$\gamma$), preventing immune-mediated apoptosis.

---

## Conclusion
TMB and UV signature are key drivers of cemiplimab response, while antigen presentation loss and interferon insensitivity drive resistance.

For full datasets, refer to [biomarker_summary.csv](file:///Users/sohith/Desktop/cemiplimab/biomarker/biomarker_summary.csv).
