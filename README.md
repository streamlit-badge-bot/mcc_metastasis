#  Modeling Metastasis
### Predicting cancer outcomes in Merkel Cell Carcinoma to improve clinical care.


Consulting project for Insight Health Data Science
with the Cutaneous Research Lab, Dr. Wesley Yu at OHSU 

## Project description 

**Modeling:** This project applies machine learning to predict risk of metastasis in Merkel Cell Carcinoma patients. 
The dataset consists of 1K patients with MCC diagnoses from the National Cancer Database (NCDB). 
The features of interest include tumor characteristics and patient demographics. 
The outcome of interest is positive case of metastasis, designated from sentinel lymph node biopsy results. 

**Web application:** Clinical prototype to guide decision-making for physicians and patients about whether to conduct invasive lymph node biopsy. 
The app deploys the ML model and provides estimated probability of metastasis based on input data from a new  patient. 

## Contents 
**notebooks:** Jupyter notebooks to walk through data cleaning, EDA, and machine learning pipeline.

**app:** Source code for Streamlit web app that deploys the machine learning model and provides results from new data.

**mcc_metastasis:** Custom functions, setup and configuration for the project.

**scripts:** Code for data cleaning and machine learning pipeline, including hyperparameter tuning, model comparisons, and model validation.

**figures:** Figures generated to display EDA and model results.

**model output:** Storing model comparison data

