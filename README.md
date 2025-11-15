# RPDA-PHC-Project

This repository contains the processed dataset and reproducible code used to analyse the associations between district-level primary healthcare (PHC) utilisation and digital readiness in South Africa.  
The data and code underpin the mixed-effects modelling and Poisson-based imputation procedures described in the accompanying research report.

---

## Repository Structure
/data/
├── RPDA_Merged_Dataset.csv # Consolidated dataset (2022–2024; 52 districts)
└── PHC_Project_Dataset.csv # Final project dataset used for analysis

/notebooks/
├── PHC_Project_Imputation.ipynb # Poisson regression imputation model and diagnostics
├── PHC_Project_EDA.ipynb # Exploratory data analysis
└── PHC_Project_Model.ipynb # Main regression model

---

## Dataset Description

**File:** `data/PHC_Project_Dataset.csv`  
**Contents:** 156 records (52 districts × 3 years)  
**Purpose:** Used for district-level analysis of PHC workload, digital access, and system capacity.  
**Provenance:** Constructed from Statistics South Africa and Health Systems Trust sources (see Appendix A in the report).  
All variables are fully de-identified and correspond to the variable definitions listed in *Appendix B* of the research report.

---

