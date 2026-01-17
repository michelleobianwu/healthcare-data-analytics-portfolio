# Hospital Executive KPI & Financial Performance Dashboard (2024)

## Project Overview
This project analyzes over 1 million hospital inpatient discharge records across New York State for the 2024 discharge year. The objective is to provide hospital leadership with executive-level operational, clinical, and financial insights to support capacity planning, service line optimization, and revenue strategy.

The project delivers a fully interactive Tableau executive dashboard supported by a cleaned and validated dataset, data dictionary, and business documentation.

---

## Business Problem
Hospitals must balance patient demand, operational efficiency, and financial sustainability. Leadership teams require clear visibility into hospital volume trends, regional demand, procedure performance, payer mix, and revenue drivers to make informed decisions.

This analysis evaluates:
- Hospital and regional inpatient demand
- Diagnosis and procedure volume trends
- Admission flow patterns
- Revenue and cost drivers
- Payer mix and reimbursement risk

---

## Dataset
**Source:** Kaggle — Hospital Inpatient Discharges  
**Records:** 1,048,576 inpatient encounters  
**Fields:** 33 variables  
**Discharge Year:** 2024  

Key fields include:
- Facility Name
- Health Service Area
- Diagnosis and Procedure Codes
- Admission Type
- Length of Stay
- Total Charges
- Total Costs
- Payment Typology (Payer Mix)
- DRG Classification

---

## Data Preparation
The dataset was cleaned and validated in Microsoft Excel.

Data quality checks included:
- Missing value validation
- Duplicate record identification and removal
- Validation of length of stay values
- Validation of charge and cost fields
- Standardization of categorical values
- Normalization of payment typology fields

Final dataset contains:
- 1,047,699 validated records
- 33 standardized fields
- No negative or invalid values

---

## Key Performance Indicators (KPIs)

### Operational KPIs
- Total Inpatient Discharges
- Average Length of Stay
- Emergency vs Elective Admission Mix
- Top Hospitals by Volume
- Regional Demand Distribution

### Clinical KPIs
- Top Diagnoses by Volume
- Top Procedures by Volume
- High-Complexity DRG Distribution

### Financial KPIs
- Total Revenue (Charges)
- Total Cost
- Revenue by DRG
- Cost by DRG
- Payer Mix Distribution

---

## Key Insights

### Hospital Volume & Regional Demand
- Patient volume is concentrated among a small number of high-volume hospitals including Mount Sinai, NYU Langone, and North Shore University Hospital.
- New York City and Long Island represent the highest regional demand for inpatient services.

### Clinical Demand Drivers
- High-volume diagnoses are driven primarily by liveborn and septicemia-related admissions.
- High-volume procedures include spontaneous vaginal delivery and cesarean sections.

### Financial Performance
- Revenue is concentrated within a subset of high-complexity DRGs including septicemia and heart failure.
- Payer mix demonstrates strong dependence on Medicare, Medicaid, and managed care programs, highlighting reimbursement risk exposure.

---

## Dashboard
The interactive executive dashboard includes three views:

### Executive Overview
- Hospital volume trends
- Regional demand distribution
- Total revenue KPI

### Operations Dashboard
- Diagnosis volume
- Procedure volume
- Admission flow
- Length of stay trends

### Financial Dashboard
- Revenue drivers by DRG
- Cost drivers by DRG
- Payer mix distribution

🔗 Tableau Public Dashboard:  
https://public.tableau.com/views/HospitalExecutiveKPIDashboardNewYorkInpatientDischarges2024/Financial_Dashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

---

## Tools Used
- Microsoft Excel (Data cleaning & validation)
- Tableau Desktop & Tableau Public (Dashboard development)
- GitHub (Version control & portfolio hosting)

---
## Documentation
A full executive KPI report is included in this repository:
- Hospital_Inpatient_Operations_Financial_KPI_Report_2024.pdf

The report includes:
- Dataset overview
- Data quality audit
- KPI framework
- Executive insights
- Operational analysis
- Financial performance analysis


## Author
Michelle Obianwu  
Healthcare Data Analyst  
