# medical-ml-icu-analysis
ICU Mortality Prediction – Applied Machine Learning Project using MIMIC-III demo data

### Dataset
I used 8 core tables from MIMIC-III, including patient demographics, ICU stays, diagnoses (ICD-9), and clinical measurements such as urine output.

### Key Features
- **Age**, **Gender**, **Ethnicity**
- **Chronic Kidney Disease (CKD)** detection via ICD codes
- **Urine Output** and **Urine Output per Day**
- **ICU Mortality** outcome

### Process
- Data cleaning and merging
- Handling missing values
- Outlier detection (IQR method)
- Feature engineering for clinical analysis
