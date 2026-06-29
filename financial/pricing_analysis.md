# Libtayo® (Cemiplimab) Geographic Pricing and Cost Analysis

## 1. Background
Biological therapeutics require substantial capital investment. Because different national healthcare systems evaluate value, negotiate pricing, and structure patient access differently, cemiplimab (Libtayo®) exhibits significant pricing variations across international markets. This document reviews the list prices, net prices, and total course treatment costs across the United States, Europe, Australia, and Japan.

---

## 2. Vial Pricing across Key Jurisdictions

### 2.1 United States
*   **Wholesale Acquisition Cost (WAC):** As of April 1, 2026, the WAC list price for a single 350 mg / 7 mL single-dose vial of cemiplimab is **$11,703.03 USD**.
*   **List vs. Net Price:** The WAC represents the list price charged to wholesalers. The actual net price paid by commercial payers, Medicare, or government programs is significantly lower due to contractually negotiated rebates, commercial discounts, and mandatory government discount schemes (such as the 340B drug pricing program or Medicaid rebates).

### 2.2 United Kingdom
*   **NHS List Price:** The official NHS list price is **£4,650 GBP** per 350 mg vial.
*   **Net Discount:** The Department of Health and Social Care (DHSC) has commercial arrangements in place through a Patient Access Scheme (PAS), which provides cemiplimab to the NHS at a confidential discounted net price.

### 2.3 Australia
*   **PBS Dispensed Price:** The dispensed price listed on the Pharmaceutical Benefits Scheme (PBS) for a 350 mg vial is approximately **$7,381.23 to $7,528.96 AUD**.
*   **Patient Contribution:** Under the PBS, eligible patients pay the standard co-payment (e.g., $31.60 or $7.70 concession), with the government subsidizing the remaining balance of the vial's cost.

### 2.4 Japan
*   **NHI Price List:** The Japanese National Health Insurance (NHI) list price is **450,437 JPY** per 350 mg vial.

---

## 3. Total Treatment Cost Calculations (1-Year Adjuvant Course)

Cemiplimab is administered at a fixed dose of 350 mg via intravenous infusion every three weeks (Q3W).

### 3.1 Dosing and Infusion Cycles
*   For advanced cSCC (unresectable/metastatic), treatment continues until disease progression or unacceptable toxicity. The median duration of treatment in clinical trials is approximately 6–9 months (approx. 9–13 cycles).
*   For high-risk resected cSCC in the adjuvant setting, the standard course is **1 year of therapy (17 cycles)**.

### 3.2 Normalized Course Cost (US WAC list price vs. International List Prices)
Calculated based on 17 cycles of 350 mg Q3W:

| Metric | United States (WAC) | United Kingdom (NHS List) | Australia (PBS List) | Japan (NHI List) |
| :--- | :--- | :--- | :--- | :--- |
| **Vial Price (Local)** | $11,703.03 USD | £4,650.00 GBP | $7,381.23 AUD | 450,437 JPY |
| **Normalized (USD)** | **$11,703.03** | **$5,812.50** | **$4,871.61** | **$3,017.93** |
| **1-Year Cost (USD)** | **$198,951.51** | **$98,812.50** | **$82,817.37** | **$51,304.81** |

*Conversion rates (2026): 1 GBP = 1.25 USD, 1 AUD = 0.66 USD, 1 USD = 150 JPY.*
*Data visualized in [financial_analysis.ipynb](file:///Users/sohith/Desktop/cemiplimab/financial/financial_analysis.ipynb).*

---

## 4. References
1.  **Regeneron Pharmaceuticals, Inc.** (2026). "Libtayo® (cemiplimab-rwlc) Commercial Price Guide." [Regeneron Price List](https://www.libtayo.com)
2.  **National Institute for Health and Care Excellence (NICE).** (2019). "Cemiplimab for treating advanced cutaneous squamous cell carcinoma (TA578)." *NICE Guideline Document*. [NICE TA578](https://www.nice.org.uk/guidance/ta578)
3.  **Australian Government Department of Health.** "Pharmaceutical Benefits Scheme (PBS): Cemiplimab." [PBS Schedule](https://www.pbs.gov.au)
4.  **Japanese Ministry of Health, Labour and Welfare.** "National Health Insurance (NHI) Drug Price List." [MHLW Portal](https://www.mhlw.go.jp)
