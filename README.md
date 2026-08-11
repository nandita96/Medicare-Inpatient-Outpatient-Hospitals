# Medicare-Inpatient-Outpatient-Hospitals
Medicare Inpatient &amp; Outpatient Healthcare Analytics Exploratory data analysis of CMS Medicare inpatient and outpatient datasets to identify cost patterns, provider-level variation, DRG/service-level outliers, and regional trends using Python, Pandas, statistical analysis, and visualization.

## Projects

### 1. Medicare Inpatient Hospitals — Provider & DRG Cost Analysis
Analysis of inpatient hospital costs across MS-DRGs, including provider-level variation, cost outliers, payment gaps, regional patterns, and predictive modeling of cost drivers.

### 2. Medicare Outpatient Hospitals — Cost & Billing Analysis (2023)
Analysis of outpatient hospital billing, Medicare payments, procedure-level variation, provider differences, outliers, and cost drivers.


2. **Medicare Outpatient Hospitals — Cost & Billing Analysis (2023)**

Dataset: CMS Medicare Outpatient Hospitals — Provider Utilization file (Dataset_OP_2023.xlsx)
Grain: one row = one hospital (Rndrng_Prvdr_CCN) × one Comprehensive APC service group (APC_Cd)

What this notebook does: cleans and audits the raw CMS file, then uses it to answer seven research questions about the gap between what hospitals bill and what Medicare actually allows/pays, where that gap is biggest, and what predicts it — closing with a peer-group outlier analysis and a machine-learning check on cost drivers.
How this notebook is organized
Section	Contents
1	Research questions
2	Data loading & cleaning
3	Data quality & outlier audit (methodology)
4	Findings Q1–Q7 (billing gap, top procedures, state/rural variation, extremes, CMS outlier payments, spending concentration)
5	Peer-group outlier detection (hospital vs. same-procedure peers)
6	Predictive modeling — what actually drives cost vs. pricing behavior
7	Executive summary
