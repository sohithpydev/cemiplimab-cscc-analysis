# Tumor Mutational Burden (TMB) in Cutaneous Squamous Cell Carcinoma (cSCC)

## 1. Background
Tumor Mutational Burden (TMB) is defined as the total number of somatic mutations (synonymous and non-synonymous) per megabase (Mb) of sequenced genomic DNA. Because somatic mutations can result in altered protein sequences (neoantigens) that are recognized by the host immune system as "non-self," tumors with high TMB are inherently more immunogenic. Cutaneous squamous cell carcinoma (cSCC) consistently ranks among the highest TMB profiles of all human malignancies, providing a robust genomic rationale for the efficacy of anti-PD-1 agents like cemiplimab.

## 2. UV-Induced Mutational Signatures (Signature 7)
The elevated TMB in cSCC is directly attributable to chronic exposure to ultraviolet (UV) radiation from sunlight.
*   **Signature 7:** The predominant mutational signature in cSCC is COSMIC Signature 7, which is characterized by:
    *   **C > T transitions** occurring at dipyrimidine sites (e.g., CpG or TpC sites).
    *   **CC > TT double substitutions**, which are highly specific pathognomonic markers of UV-induced pyrimidine dimer formation and subsequent error-prone replication.
*   **Functional Impact:** These mutations are distributed widely throughout the cancer genome, inactivating key tumor suppressor genes (e.g., *TP53*, *NOTCH1*, *NOTCH2*) and generating a diverse pool of immunogenic neoantigens that stimulate cytotoxic T-cell responses.

## 3. Relationship with Cemiplimab Response
Exploratory biomarker analyses from the EMPOWER-CSCC-1 trial evaluated the relationship between pre-treatment TMB (measured via whole exome sequencing) and clinical outcomes.

### 3.1 Median TMB Values (Responders vs. Non-Responders)
In the biomarker substudy of EMPOWER-CSCC-1, responders exhibited significantly higher baseline TMB compared to non-responders:
*   **Group 3 (350 mg Q3W fixed-dose, n=28):**
    *   **Responders (n=13):** Median TMB of **61.4 mutations/Mb**.
    *   **Non-Responders (n=15):** Median TMB of **13.7 mutations/Mb**.
*   **Group 1 (3 mg/kg Q2W weight-based, n=30):**
    *   **Responders (n=15):** Median TMB of **53.2 mutations/Mb**.
    *   **Non-Responders (n=15):** Median TMB of **19.4 mutations/Mb**.

*Data compiled in [biomarker_summary.csv](file:///Users/sohith/Desktop/cemiplimab/biomarker/biomarker_summary.csv) and visualized in [biomarker_analysis.ipynb](file:///Users/sohith/Desktop/cemiplimab/biomarker/biomarker_analysis.ipynb).*

### 3.2 TMB Thresholds
While the FDA has approved pembrolizumab for any solid tumor with TMB $\ge$ 10 mut/Mb, in cSCC, the baseline median TMB is so high (~50 mut/Mb) that a threshold of 10 mut/Mb is met by over 80% of patients. Consequently, in cSCC:
*   Thresholds higher than the standard 10 mut/Mb (e.g., $\ge$ 45 mut/Mb) have been evaluated to better stratify responders.
*   However, because some patients with TMB below these higher thresholds still achieve durable complete responses, TMB is not utilized as a strict exclusionary biomarker in clinical labeling.

## 4. Advantages and Limitations
*   **Advantages:**
    *   Strong biological correlation with neoantigen burden and T-cell activation.
    *   Quantifiable and reproducible via standardized Next-Generation Sequencing (NGS) assays.
*   **Limitations:**
    *   **High Sequencing Cost:** Whole Exome Sequencing (WES) or large targeted panels (e.g., FoundationOne CDx) are expensive and time-consuming.
    *   **Overlap in Response:** The substantial overlap in TMB distributions between responders and non-responders means TMB cannot serve as a binary predictor of success.
    *   **Clonal vs. Subclonal Mutations:** TMB counts all mutations, but subclonal mutations (present in only a subset of tumor cells) are less effective at driving a robust immune response compared to clonal mutations.

## 5. References
1.  **Rischin, D., et al.** (2020). "Phase 2 study of cemiplimab in patients with metastatic cutaneous squamous cell carcinoma: primary analysis of fixed-dosing, long-term outcome of weight-based dosing." *Journal for ImmunoTherapy of Cancer*, 8(2), e000775. PMID: [33027604](https://pubmed.ncbi.nlm.nih.gov/33027604) | DOI: [10.1136/jitc-2020-000775](https://doi.org/10.1136/jitc-2020-000775)
2.  **Chalmers, Z. R., et al.** (2017). "Analysis of 100,000 human cancer genomes reveals the landscape of tumor mutational burden." *Genome Medicine*, 9(1), 34. PMID: [28427475](https://pubmed.ncbi.nlm.nih.gov/28427475) | DOI: [10.1186/s13073-017-0424-2](https://doi.org/10.1186/s13073-017-0424-2)
3.  **Alexandrov, L. B., et al.** (2020). "The repertoire of mutational signatures in human cancer." *Nature*, 578(7793), 94-101. PMID: [32025018](https://pubmed.ncbi.nlm.nih.gov/32025018) | DOI: [10.1038/s41586-020-1943-3](https://doi.org/10.1038/s41586-020-1943-3)
