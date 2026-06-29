# Changelog

All notable changes to this project will be documented in this file.

## [1.0.0] - 2026-06-29
### Added
*   **Phase 1: Mechanism of Action & Pivotal Trials**
    *   Curated datasets for drug pharmacology and clinical trials (`data/cemiplimab_pharmacology.csv`, `data/empower_cscc_1_efficacy.csv`, `data/c_post_efficacy.csv`).
    *   Analyzed efficacy profiles in `notebooks/01_clinical_efficacy.ipynb`.
    *   Wrote MoA and trial results documentation in `docs/01_mechanism_and_efficacy.md`.
*   **Phase 2: Clinical Development & Regulatory Affairs**
    *   Added datasets for regulatory milestones, safety, and subgroups (`data/cemiplimab_regulatory_history.csv`, `data/empower_cscc_1_subgroups.csv`, `data/cemiplimab_safety_ae_profile.csv`).
    *   Developed safety and subgroups analysis in `notebooks/02_regulatory_safety.ipynb`.
    *   Wrote comprehensive safety review in `docs/02_regulatory_and_safety.md`.
*   **Phase 3: Biomarkers & Precision Medicine**
    *   Added biomarkers dataset (`biomarker/biomarker_summary.csv`).
    *   Created biomarker comparison heatmap and TMB boxplot in `biomarker/biomarker_analysis.ipynb`.
    *   Wrote detailed precision medicine reports (`biomarker/pd_l1.md`, `biomarker/tumor_mutation_burden.md`, `biomarker/immune_microenvironment.md`, `biomarker/predictive_biomarkers.md`, `biomarker/biomarker_limitations.md`).
*   **Phase 4: Intellectual Property & Exclusivity**
    *   Added patent database (`IP/patent_summary.csv`).
    *   Developed exclusivity timeline Gantt chart in `IP/patent_timeline.ipynb`.
    *   Wrote patent and licensing reports (`IP/patent_overview.md`, `IP/patent_landscape.md`, `IP/exclusivity.md`, `IP/biosimilar_landscape.md`).
*   **Phase 5: Commercial Landscape & Market Positioning**
    *   Added competitor and commercial database (`commercial/commercial_summary.csv`).
    *   Created revenue growth and response comparison plots in `commercial/commercial_analysis.ipynb`.
    *   Wrote commercial strategy and guidelines reports (`commercial/commercial_strategy.md`, `commercial/competitive_landscape.md`, `commercial/branding_and_positioning.md`, `commercial/treatment_guidelines.md`, `commercial/kols.md`).
*   **Phase 6: Financial Analysis & Market Economics**
    *   Added financial summary dataset (`financial/financial_summary.csv`).
    *   Created currency normalized pricing comparisons in `financial/financial_analysis.ipynb`.
    *   Wrote pricing, revenue, reimbursement, and health economics reports (`financial/pricing_analysis.md`, `financial/market_size.md`, `financial/revenue_analysis.md`, `financial/reimbursement.md`, `financial/health_economics.md`).
*   **Phase 7: Post-launch Evidence & Long-term Outcomes**
    *   Added RWE registry database (`post_launch/post_launch_summary.csv`).
    *   Created trial vs. RWE and survival benchmark plots in `post_launch/post_launch_analysis.ipynb`.
    *   Wrote post-approval evidence and pipeline combination reports (`post_launch/real_world_evidence.md`, `post_launch/long_term_safety.md`, `post_launch/pharmacovigilance.md`, `post_launch/adoption.md`, `post_launch/guideline_updates.md`, `post_launch/future_directions.md`).
*   **Phase 8: Repository Finalization**
    *   Added open-source metadata standards (LICENSE, CONTRIBUTING, CHANGELOG, CODE_OF_CONDUCT).
    *   Added requirements.txt, environment.yml, and references/ data catalogs.
    *   Created technical blog posts and CI/CD GitHub Actions workflow.
