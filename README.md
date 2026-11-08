# Egypt Medium-Term Debt Management Strategy (MTDS) & External Debt Monitor

An institutional sovereign debt monitoring framework, macroeconomic risk simulator, and investor relations intelligence suite for the **Arab Republic of Egypt's Medium-Term Debt Strategy (MTDS 2026–2029)**.

This repository provides an integrated platform to monitor sovereign debt trajectory, reconcile reporting perimeters between fiscal and monetary authorities, decompose foreign-exchange stock adjustments, and model debt-service sensitivity under macro-fiscal shocks.

---

## Repository Structure

```text
MoF_MTDS_Monitor/
├── .gitignore                                          # Standard repository exclusions
├── README.md                                           # Project guide and architecture documentation
├── GoE_MTDS_2026_2029_External_Debt_Monitor.xlsx       # Master financial model & risk simulator
├── MTDS_External_Debt_Reconciliation_Report.md         # Comprehensive statistical audit & perimeter bridge
├── Official_Memo_MTDS_External_Debt_Performance_AR_EN.md # Official debt performance memo (Bilingual: AR / EN)
├── Investor_Roadshow_Brief_&_Minutes_Pack.md           # 5-slide fixed-income roadshow brief & minutes template
├── Macro_IR_Executive_Dashboard.png                    # Executive dashboard visualization preview
├── csv_historical_budget_debt_series.csv               # Historical debt stock time series
├── csv_macro_fiscal_ir_indicators.csv                  # Macro-fiscal and credit rating indicators
├── csv_mof_cbe_perimeter_reconciliation.csv            # MoF vs. CBE institutional perimeter bridge
├── csv_mtds_targets_and_shocks.csv                     # MTDS strategy targets and sensitivity shocks
└── csv_project3_forensic_checks.csv                    # Automated integrity checks and audit log
```

---

## Executive Financial Model Architecture (`.xlsx`)

The financial engine features **866 live Excel formulas** and 244 cross-sheet references across six integrated worksheets:

| Sheet | Worksheet Name | Scope & Analytical Functionality |
|:---:|---|---|
| **Tab 1** | `Readme_&_MTDS_Controls` | Model controls, 4 methodology vintage dropdowns, currency composition targets, and MTDS strategy benchmarks. |
| **Tab 2** | `MoF_vs_CBE_Perimeter_Bridge` | MoF component reconciliation, dual-basis YoY reduction, institutional sector bridge, and securities diagnostics. |
| **Tab 3** | `Historical_Debt_&_FX_Decomp` | 9-period historical debt stock series, GDP ratio vintages, and FX valuation decomposition (net dollar flows vs. currency translation). |
| **Tab 4** | `MTDS_Cost_Risk_Shock_Simulator` | Dynamic sensitivity matrices modeling debt/GDP and interest service under interest-rate (+100–300 bps) and FX (+10–30%) shocks. |
| **Tab 5** | `Macro_IR_&_Executive_Dashboard` | High-level KPI summary cards, debt maturity profiles, currency composition, and fiscal indicator ledgers. |
| **Tab 6** | `Forensic_Audit_&_QA_Log` | 10 live automated formula QA rules (`OK - RECONCILED`) and complete 46-item forensic discrepancy tracking ledger (F001–F046). |

### Core Quantitative Insights:
1. **The USD 90.6 Billion Perimeter Bridge:** Complete analytical reconciliation bridging MoF budget-sector external debt (**USD 76,148M**) with CBE economy-wide external debt (**USD 166,748M**), allocating USD 3,415M to central government differences and USD 79,236M to central bank, banking, and non-government sectors.
2. **EGP Stock-Change Decomposition:** Rigorous mathematical breakdown of the EGP 148.55B annual debt reduction into:
   * **USD Stock Effect:** −EGP 120.41B (81.08% of explained movement).
   * **FX Translation Effect:** −EGP 28.09B (18.92% of explained movement).
3. **Macro-Fiscal Stress Testing:** Sensitivity modeling under combined shocks (e.g., +20% FX depreciation paired with +200 bps floating foreign rates), illustrating external interest rising to EGP 306.82B (1.43% of GDP).

---

## Institutional Deliverables

* **Bilingual Executive Memorandum:** Fully drafted for review by the Head of the Debt Management Unit in both English and Arabic: [Official_Memo_MTDS_External_Debt_Performance_AR_EN.md](Official_Memo_MTDS_External_Debt_Performance_AR_EN.md).
* **Investor Relations Roadshow Pack:** 5-slide briefing pack with institutional talking points, visual specifications, and simulated investor meeting minutes: [Investor_Roadshow_Brief_&_Minutes_Pack.md](Investor_Roadshow_Brief_&_Minutes_Pack.md).
* **Forensic Audit & Research Report:** Security-level citations, statistical bulletin reconciliations, and perimeter analysis: [MTDS_External_Debt_Reconciliation_Report.md](MTDS_External_Debt_Reconciliation_Report.md).

---

## Primary Regulatory Sources

Data is compiled exclusively from primary official publications:
* **Ministry of Finance:** Medium-Term Debt Management Strategy (MTDS 2026–2029), Budget Sector Statistical Debt Bulletins (June 2025, Dec 2025, March 2026, June 2026), and Monthly Financial Reports.
* **Central Bank of Egypt:** External Position Reports, National Summary Data Page (NSDP), Balance of Payments Releases, and Official Net International Reserve (NIR) announcements.
* **Credit Rating Agencies:** Official affirmations and rating releases from Moody's (`B3 / Positive`), S&P (`B/B / Stable`), and Fitch (`B / Stable`).

---

## Author

**Zyad Magdy**  
*Quantitative Research & Sovereign Debt Analysis*
