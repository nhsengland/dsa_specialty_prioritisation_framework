# dsa_specialty_prioritisation_framework
Data Science Accelerator project exploring a data-driven approach to identifying and prioritising unmet health need using population health, inequalities and NHS system data.

## PROOF OF CONCEPT
This repository contains exploratory work completed as part of the NHS England Data Science Accelerator programme. The outputs should be interpreted as comparative screening signals and not as definitive measures of unmet need or prioritisation recommendations.

## Overview
This repository contains the code and outputs (poster and slide) developed as part of the NHS England Data Science Accelerator (DSA) programme.

The project explored whether routinely available NHS system data could provide an additional evidence layer to support conversations about research and innovation (R&I) prioritisation and unmet need.

Rather than replacing clinical expertise, stakeholder engagement or policy priorities, the aim was to test whether operational NHS data could be transformed into a transparent and reproducible framework for identifying specialties and geographies that may warrant further investigation.

## Project Aim
To develop and test a reproducible analytical framework that:
- integrates routine NHS operational datasets
- generates comparable specialty-level signals
- explores geographic variation across Integrated Care Boards (ICBs)
- visualises outputs through interactive Power BI dashboards

## Proof of Concept Scope
The initial proof of concept included:

### Clinical Specialties
- Cardiovascular
- Respiratory
- Trauma & Orthopaedics
- Gynaecology

### Operational Indicators
- Access pressure (referral to treatment (RTT) > 18 weeks)
- Scale of pressure (incomplete RTT pathways per 100,000)
- Hospital burden
    - emergency length of stay >6 days
    - elective length of stay >6 days
- Contextual indicators
    - population size
    - index of multiple deprivation
- Geography (42 integrated care boards - as of 2024/25 data) - since changed to 36 ICBs but has not been fully adopted across datasets

## Repository Contents
### Python Scripts
The repository contains scripts used to:
- clean and harmonise datasets
- perform data-quality checks
- generate specialty-level signals
- test alternative analytical methods
- produce dashboard-ready outputs

Key analytical components include:
- specialty signal generation
- rank-based approaches
- composite signal approaches
- sensitivity analysis
- geographic analysis
- contextual analysis

### Supporting files
- DSA poster (pdf)
- DSA lightening talk slide (PDF)

## Key Findings
### National View
Trauma & Orthopaedics demonstrated the strongest comparative signal across the specialties tested.
The overall ordering remained broadly stable across alternative weighting approaches and sensitivity-testing scenarios.

### Regional View
Local signal profiles varied across ICBs.
The leading specialty within an individual ICB did not always mirror the national ordering, demonstrating the value of exploring both national and regional perspectives.

### Data Quality
Data quality, availability and comparability emerged as major findings in their own right.
Effort was required to:
- align ICB geographies
- manage missing data
- harmonise indicator definitions
- ensure fair comparisons between specialties

## Important Limitations
This project does not:
- measure unmet need directly
- identify causes of variation
- prioritise innovations automatically
- replace clinical expertise
- replace policy or strategic priorities
The outputs are intended as comparative screening signals to support further investigation.

## Future Development
Potential next steps include:
- inclusion of additional specialties
- development of outpatient and day-case indicators
- time-series analysis
- clinical validation of indicator selection and weighting
- enhanced inequalities analysis
- exploration of links with innovation prioritisation and adoption

## Reproducibility
The project was developed using:
- Python
- Git and GitHub version control
The workflow was designed to be transparent, reproducible and extensible.

## Author
Helen Bauckham
 Horizon Scanning and Demand Signalling Team : NHS England
Data Science Accelerator (DSA) Cohort 2026
Mentor: Marcos Fabietti