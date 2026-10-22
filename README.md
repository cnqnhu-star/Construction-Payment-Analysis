# Construction Payment Application & Cash Flow Analysis

## Project Overview
This project showcases the data transformation and visualization of a 13-milestone payment application for a commercial construction project. The objective was to convert fragmented, unstructured legacy ledgers (originally in Vietnamese) into a clean, standardized English dataset to monitor cash flow, track WBS (Work Breakdown Structure) progress, and identify payment anomalies.

## Methodology & Data Transformation
- **Data Extraction:** Raw data was extracted from legacy Excel sheets containing mixed transactional, advance payment, and subtotal rows.
- **Data Cleansing:** Used Excel tools to filter out double-counting rows, standardize date formats, and map Vietnamese terms to standard international construction accounting terms (e.g., *Advance Payment Deductions, Retention Value, Net Payable*).
- **Data Modeling:** Structured the cleaned data into three distinct analytical views: Executive Summary, Detailed Ledger, and WBS Matrix.

---

## Dashboard & Insights

### 1. Executive Payment Summary
<img width="1288" height="498" alt="SummaryofPayment" src="https://github.com/user-attachments/assets/2fd978a9-aba4-4bfc-8770-535016a0b106" />

*   **Description:** A condensed summary of 13 payment applications, tracking Net Payable amounts after deducting advances and retentions.
*   **Insight:** Tracked a consistent monthly billing cycle (Apr 2025 - Jul 2026). The highest net realization occurred in Milestone 09 (approx. 9.7 Billion VND) due to major structural progress.

### 2. Detailed Progress Payments Ledger
<img width="1616" height="639" alt="ProgressPayments" src="https://github.com/user-attachments/assets/788ee933-cc46-40bd-8663-d2b3e0118442" />

*   **Description:** A detailed breakdown of Work Approved (Excl. VAT), Total Approved Value (Incl. VAT), Advance Payment Recovery, and Retentions. 
*   **Insight:** Out of a total approved work value of **65.6 Billion VND**, the actual Net Payable cash inflow was **61.6 Billion VND**. The 4 Billion VND gap is primarily driven by 5% retention and advance recovery, highlighting the importance of cash flow forecasting.

### 3. WBS Matrix: Work Value by Task Description
<img width="1862" height="530" alt="ValueofWorkCompleted" src="https://github.com/user-attachments/assets/b555f0dd-3a6a-44ff-b0ad-55f817b161e9" />

*   **Description:** A dynamic matrix mapping payment amounts across various construction tasks (Foundation, Structural Work, Mall Area, Roof Drainage, etc.) for each milestone.
*   **Insight:** The matrix reveals that **Structural Work** and **Reinforced Concrete Works for Mall Area** are the largest cost drivers. Milestone 09 was a critical month where structural work peaked, while Milestones 11-13 saw an increase in "Miscellaneous" tasks, indicating project finalization and snagging phases.

---

## Repository Structure
- `/Images`: Contains screenshots of the payment summaries and WBS matrix.
- `/Raw_Data`: Contains the original, unmodified Excel file for reference.

## Key Skills Demonstrated
- **Financial Analysis:** Cash flow tracking, retention analysis, WBS cost allocation.
- **Data Cleaning:** Transforming unstructured legacy data into flat tables.
- **Documentation:** Bilingual translation (Vietnamese to English) of construction accounting terms.
