# Cancer Intelligence Report | Power BI Dashboard

**Tool:** Power BI | **Client:** Graceland Clinic | **Period:** 2020 - 2026

---

## Project Overview

This dashboard was specifically built to help Graceland Clinic Executives make sense of their patient data across three core areas: Patient admissions, clinical outcomes, and financial performance. The goal was to turn raw records into a clear picture of what is happening with cancer cases at the clinic, the quality of service and as well as identifying where attention is mostly needed.

This report is structured across three pages, each focused on a different lens of the data.

---

## Dashboard Pages


### Page 1: Patients Overview
<img width="1312" height="753" alt="Screenshot 2026-05-30 042711" src="https://github.com/user-attachments/assets/a47c9e44-e15b-4ba9-8b10-01f8c79c566b" />
This page answers the basic but important question: who are the patients, and what is happening with admissions over the years?

**Key Numbers (2023)**

| Metric | Value |
|---|---|
| Total Registered Patients | 1,629 |
| Active Cancer Cases | 807 |
| Readmission Rate | 48.8% |
| Avg Length of Stay | 11 days |
| Complication Rate | 49.2% |

The clinic saw a slight drop in registered patients compared to the previous year (1,640 in 2022 vs 1,629 in 2023), a 0.7% decline. While small, it is worth monitoring over time.

**Readmission Reasons**

Nearly half of all patients were readmitted after discharge, however, a deeper analysis reviewed the top reasons behind this outrageous readmission rate at Graceland Clinic,  this reasons were:

- Treatment Toxicity: 173 patients
- Infection: 162 patients
- Dehydration: 159 patients
- Pain Crisis: 155 patients
- Recurrence: 146 patients

Treatment toxicity being the leading cause of readmission points to a potential gap in post discharge care and medication management at the facility, Graceland Clinic executives needs to adress this issue as soon as possible or risk bad reputation. Together, these five reasons account for 795 readmitted patients.

**Patient Demographics**

Gender split across the patient base:
- Male: 799 (49.05%)
- Female: 634 (38.92%)
- Unspecified: 196 (12.03%)

Age distribution:
- Adults (30 to 59): 651 (39.96%)
- Young Adults (18 to 29): 702 (43.09%)
- Older Adults (60+): 276 (16.94%)

Young adults make up the largest age group patients at Graceland, which is actually a bit shocking, given the fact that cancer is often associated with older populations.

**Country Breakdown**

Patient intake is spread across 8 countries. Brazil leads with 213 patients, followed closely by Canada (209), USA (208), and Kenya (206). Nigeria sits at 194. The distribution is relatively even, suggesting the clinic serves a diverse international population.

---

### Page 2: Diagnoses and Clinical Outcomes
<img width="1312" height="762" alt="Screenshot 2026-05-30 042756" src="https://github.com/user-attachments/assets/c2ada4f6-1a0b-4411-a537-2d10ac4d975e" />

This page focuses on what types of cancer patients have, how long they survive on average, and how their quality of life compared across cancer types.

**High-Level Numbers**

| Metric | Value |
|---|---|
| Total Active Cancer Cases | 5,008 |
| Avg Survival Days | 1,521 |
| Avg Quality of Life Score | 55.19 |

**Patients per Cancer Type**

| Cancer Type | Patients |
|---|---|
| Colorectal Cancer | 2,280 |
| Breast Cancer | 2,257 |
| Leukemia | 1,121 |
| Lung Cancer | 1,090 |
| Melanoma | 1,088 |
| Prostate Cancer | 1,088 |
| NSCLC | 1,076 |

Colorectal and Breast Cancer account for a significant portion of the total caseload.

**Diagnosis Delay**

On average, patients waited between 159 and 166 days from symptom onset to diagnosis. Prostate Cancer had the longest average delay at 166 days, while Lung Cancer had the shortest at 159 days. Across all cancer types, the delays were consistently high, which is a concern worth flagging for early detection initiatives.

**Active vs. Inactive (Deceased) Cases**

| Cancer Type | Active | Deceased | Avg QOL |
|---|---|---|---|
| Prostate Cancer | 540 | 548 | 56.14 |
| Colorectal Cancer | 1,150 | 1,130 | 55.56 |
| Breast Cancer | 1,135 | 1,122 | 55.43 |
| Lung Cancer | 546 | 544 | 55.23 |
| NSCLC | 532 | 544 | 55.14 |
| Melanoma | 540 | 548 | 54.41 |
| Leukemia | 565 | 556 | 53.80 |

The active and deceased numbers are very close across all cancer types, suggesting relatively high mortality rates. Leukemia shows the lowest quality of life score at 53.80.

**Quality of Life by Cancer Type**

Prostate Cancer patients reported the highest average quality of life score (56.1), while Leukemia patients reported the lowest (53.8). The spread is narrow, which may reflect consistent care quality across cancer types at this clinic.

**Treatment Tolerability**

Across all cancer types, treatment tolerability scores were tightly clustered between 4.97 and 5.05, pointing to a fairly uniform patient experience with treatment side effects regardless of cancer type.

---

### Page 3: Finance and Revenue
<img width="1311" height="762" alt="Screenshot 2026-05-30 042841" src="https://github.com/user-attachments/assets/4d0f1618-ae92-4d93-92fa-d3cd64c4cd2b" />

This page covers the clinic's financial picture, including how revenue is generated, how insurance claims are processed, and how patients prefer to pay.

**High-Level Numbers**

| Metric | Value |
|---|---|
| Total Revenue | 849.2M |
| Avg Out of Pocket Cost per Patient | 8.81K |
| Claim Approval Rate | 25.4% |
| Bad Debt Rate | 49.9% |

The claim approval rate of 25.4% is notably low. Three out of four insurance claims are not being fully approved, which directly contributes to the bad debt rate sitting at nearly 50%. This is a significant financial risk for the clinic.

**Revenue by Treatment Type**

| Treatment | Revenue |
|---|---|
| Targeted Therapy | 108.6M |
| Emergency Care | 107.9M |
| ICU Admission | 107.8M |
| Chemotherapy | 106.0M |
| Immunotherapy | 106.0M |
| Radiation | 105.2M |
| Diagnostics | 105.0M |
| Surgery | 102.6M |

Revenue is distributed fairly evenly across treatment types, with Targeted Therapy coming in at the top. No single treatment dominates, which reflects a diverse treatment mix.

**Insurance Claims Breakdown**

| Status | Share |
|---|---|
| Denied | 25.29% |
| Approved | 24.81% |
| Partially Approved | 25.06% |
| Pending | 24.83% |

Claims are almost equally split across all four statuses. The fact that approved claims are a minority highlights a systemic issue in the clinic's insurance claim process or in the policies their patients hold.

**Policy Type vs. Claim Status**

Across all four policy types (Self-pay, Employer Sponsored, Private, and Public), the distribution of Approved, Denied, Partially Approved, and Pending claims is nearly identical. No policy type stands out as more favorable, which suggests the issue may lie with internal claim management rather than specific insurer behavior.

**Patient Payment Preferences**

| Channel | Patients |
|---|---|
| Card | 3,993 |
| Bank Transfer | 3,974 |
| Mobile Money | 3,967 |
| Insurance | 3,945 |
| Cash | 3,845 |

Payment preference is evenly spread, which means the clinic needs to maintain support for all channels without over-investing in any one. Cash remains the least preferred option.

---

## Key Takeaways | Recommendations

1. The readmission rate (48.8%) is high and driven primarily by treatment-related complications. A post-discharge support program could reduce these numbers.

2. Diagnosis delays are consistently long across all cancer types (averaging over 160 days). Earlier detection pathways could improve survival outcomes.

3. Only 25.4% of claims are fully approved, and the bad debt rate is close to 50%. The clinic needs a focused review of its insurance claim strategy.

4. Young adults represent the largest patient age group, which may warrant targeted outreach and awareness campaigns for this demographic.

5. Leukemia patients show the lowest quality of life and highest mortality relative to active cases, suggesting this group may benefit from more focused clinical attention.

---

## Tools Used

- Power BI (Power Query, Data modeling, DAX measures, report design)
- Note: This is a synthetic dataset. Survival metrics are simulated and may not fully reflect real world clinical outcomes and correlation dependency, However this goes to show my deep analysis skills.

---

*Built by Anthony Wayas | [Gmail: Anthonywayas123@gmail.com] | [X: @AnthonyWayas1](https://x.com/AnthonyWayas1) | [LinkedIn: Anthony Wayas1](https://linkedin.com/in/AnthonyWayas1)*
