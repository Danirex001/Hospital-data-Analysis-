# Hospital-data-Analysis-
A Comprehensive data Analysis of a Hospital 

# 🏥 Hospital Encounter Data Analysis

This project explores patient encounter data to uncover insights about hospital utilization, patient demographics, and clinical care. Using Python, pandas, and visualization libraries, the analysis addresses key questions around **length of stay, admission types, readmissions, and medical specialty trends**.

## 📊 Dataset

The dataset contains records of hospital encounters with the following key columns:

* **encounter_id** – Unique identifier for the hospital visit
* **patient_nbr** – Patient identifier
* **race, gender, age, weight** – Patient demographics
* **admission_type_id, discharge_disposition_id, admission_source_id** – Admission and discharge details
* **time_in_hospital** – Length of stay (days)
* **prayer_code, medical_specialty** – Coded patient and physician attributes
* **num_lab_procedures, num_procedures, num_medications** – Care details
* **number_outpatient, number_emergency, number_inpatient** – Utilization history
* **age_mid, weight_mid** – Midpoint values for age and weight groups

## 🎯 Objectives

This project aims to answer the following research questions:

1. What is the demographic distribution of patients (race, gender, age)?
2. Which groups tend to stay longer in the hospital?
3. How do admission types, sources, and discharge dispositions differ across patients?
4. What is the relationship between lab procedures, medications, and length of stay?
5. Which medical specialties are associated with higher readmissions?
6. Can we predict hospital **length of stay** from patient and clinical variables?
7. Can we identify **high hospital utilizers** (patients with multiple admissions)?

## 🔍 Methods

The analysis was carried out in multiple stages:

1. **Data Cleaning & Preprocessing**

   * Handling missing values
   * Encoding categorical variables
   * Creating derived features (e.g., age_mid, weight_mid)

2. **Exploratory Data Analysis (EDA)**

   * Distributions of demographics and admission types
   * Correlation between hospital stay and medical procedures
   * Trends in readmissions across specialties

3. **Modeling**

   * **Regression**: Predicting hospital length of stay.

4. **Visualization & Reporting**

   * Histograms, bar charts, boxplots
   * Correlation heatmaps
   * Feature importance for predictive models

## 📈 Key Insights (Illustrative)

* **Demographics**: Most patients are between **70-80 years**; slightly more **female** patients.
* **Length of Stay**: Older patients and those with higher weight categories stay longer.
* **Admission Patterns**: **Emergency admissions** are very low  (>25%).
* **Procedures & Medications**: Higher counts deosn't correlate with longer hospital stays in our dataset. That is because the majority of the cases are not critical cases. 
* **Readmissions**: Patients under **dentistry and Pyscjiatry** specialties show more repeat visits.
* **Predictive Modeling**: Age, admission type, and prior hospitalizations are strong predictors of length of stay.

## 📜 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.


## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests for improvements.


## 🙌 Acknowledgments

* Inspired by real-world hospital data use cases
* Analysis powered by **Python, pandas, matplotlib, seaborn, scikit-learn**
