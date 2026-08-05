# 🏥 Project 1: National Health Analysis Dashboard

> **Project 1 of my Data Analytics Portfolio.** A 3-page Power BI dashboard analyzing hospital admissions, patient demographics, and treatment costs across 10 major U.S. hospitals — built to demonstrate end-to-end skills in data modeling, DAX, and interactive dashboard design.

---

## 📁 Project Structure

```
Healthcare-Project/
│
├── Health ppt.pptx                        → Presentation summary of findings
├── Healthcare Analysis Dataset.xlsx        → Raw/cleaned source data
├── Healthcare_DAX_Documentations.pdf       → DAX formulas & measure documentation
├── National Health Analysis Dashboard.pbix → Power BI report file (main deliverable)
├── Key Trends.png                          → Screenshot: Page 1 of dashboard
├── Patients Demographics.png               → Screenshot: Page 2 of dashboard
└── Treatment & Cost.png                    → Screenshot: Page 3 of dashboard
```

> **Note:** All PNG screenshots live directly in this folder (not in a subfolder), so the README links below point to `./filename.png` — keep the images alongside `README.md` when uploading to GitHub or they won't render.

The report has **3 pages** with a consistent navigation bar (Patients Demographics / Key Trends / Treatment & Cost) and shared KPI cards on every page: **Admitted Patients, Rooms/Bedspace, Avg Billing Amount, Doctors, Avg LOS (Days), Avg Age**.

---

## 📊 Dashboard Overview

### 1. Key Trends
<img src="./Healthcare-Project/Key%20Trends.png" alt="Key Trends" width="800"/>

- 55,500 admitted patients, 40,341 doctors, 400 rooms/bedspace, avg LOS 15.51 days, avg billing $25,539.
- **Admission by Day Type**: Weekday 71.49% vs Weekend 28.51%.
- **LOS Buckets**: Extended Stay (15+) is the largest bucket at **53.16%**, followed by Long Stay (8–14) at 23.44%, Moderate Stay (4–7) at 13.48%, and Short Stay (1–3) at 9.91%.
- **Monthly/Daily Breakdown**: Fairly even distribution across months (~4,500–4,900/month); August highest (4,832), February lowest (4,255); Wednesday busiest weekday overall (7,982 total).
- **Billing by admission type**: Elective, Emergency, and Urgent billing fluctuate seasonally between ~$24,800–$26,300 with no single type consistently highest.

### 2. Patients Demographics
<img src="./Healthcare-Project/Patients%20Demographics.png" alt="Patients Demographics" width="800"/>

- **Blood group**: A+ most common (11.1K); more females than males across most groups.
- **Diagnostic results**: Abnormal 55% (31K), Inconclusive 35% (19K), Normal only 10% (5,550) — majority of admitted patients show abnormal or inconclusive results.
- **Hospital breakdown**: Houston Methodist Hospital leads with 20,402 total patients — over 3x the next largest, Johns Hopkins (11,268). Diabetes (5,104) and Hypertension (5,057) are its top conditions.
- Interactive medical condition selector with descriptive info panel (e.g., Arthritis).

### 3. Treatment & Cost
<img src="./Healthcare-Project/Treatment%20%26%20Cost.png" alt="Treatment & Cost" width="800"/>

- **Billing by Length of Stay**: Extended Stay (15+) patients account for the majority of billing (~0.25bn per admission type), far above Short Stay (~0.04–0.05bn).
- **Billing by hospital**: Houston Methodist leads at 0.52bn — more than double Johns Hopkins (0.29bn) and roughly triple UCLA (0.18bn), consistent with its patient volume.
- **Top medication**: Aspirin (11,140), closely followed by Ibuprofen, Lipitor, Paracetamol, and Penicillin — fairly even distribution.
- **Condition × medication table**: Diabetes and Hypertension have the highest totals (13,875 each), matching their prominence in the Demographics page.

---

## 🧵 Key Insight / Story

1. **Key Trends** → Extended stays (15+ days) are the largest LOS bucket (53%).
2. **Demographics** → Houston Methodist has by far the most patients, mostly with abnormal diagnostic results.
3. **Treatment & Cost** → Extended stays and Houston Methodist both drive the highest billing.

**Conclusion**: Length of stay and hospital volume are the two biggest cost levers in this dataset. There is also a notable capacity concern — 400 rooms/bedspace against 55,500 admitted patients.

---

## 🛠️ Tools Used
- **Power BI** — dashboard build, DAX measures, interactivity
- **Excel** — source dataset
- **PowerPoint** — findings presentation

---
