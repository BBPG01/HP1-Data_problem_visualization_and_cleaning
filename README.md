# HP1-Data_problem_visualization_and_cleaning
Hospital Patient Data Cleaning Project   This project focuses on cleaning and preparing hospital patient data for analysis. The dataset includes patient IDs, names, ages, categories of medical care, and expenses per category. The goal is to ensure data consistency, standardization, and readiness for generating hospital KPIs.

---

# Hospital Patient Data Cleaning Project

## 📖 Project Overview
Hospitals rely on accurate and consistent patient data to design monitoring programs, optimize resource allocation, and improve healthcare outcomes.  
This project demonstrates how to clean, transform, and validate patient records using Python, preparing them for analysis and KPI generation.

## 🎯 Objectives
- Clean patient profiles (remove spaces, underscores, and standardize names).
- Convert patient ages to integers.
- Standardize categories of care to lowercase.
- Calculate total medical expenses per patient.
- Validate data consistency and handle errors gracefully.
- Prepare the dataset for hospital KPIs.

## 📊 Dataset
The dataset contains:
- **patient_id**: Unique identifier for each patient.  
- **patient_name**: Patient’s full name.  
- **patient_age**: Age of the patient.  
- **categories_of_care**: Medical services used (Emergency, Consultation, Surgery, Pharmacy, Lab).  
- **expenses_per_category**: Total expenses per category.  

Example:
```python
patients = [ 
    ['1001', ' juan_perez ', 45.0, ['EMERGENCY', 'CONSULTATION', 'PHARMACY'], [1200, 450, 230]],
    ['1002', ' maria lopez ', 30.0, ['CONSULTATION', 'SURGERY'], [600, 3500]],
    ['1003', ' carlos_gomez ', 52.0, ['EMERGENCY', 'CONSULTATION', 'LAB'], [2000, 500, 300]],
]
