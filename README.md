# Combined Assessment of Risk Encountered in Surgery (CARES) Project (SingHealth)

This project explores the *Chan et al. (2018)* study on the **Combined Assessment of Risk Encountered in Surgery (CARES)** risk calculator.

CARES is a clinical risk prediction tool developed to estimate the likelihood of critical postoperative outcomes, including:

- Post-surgical mortality  
- Unplanned Intensive Care Unit (ICU) admission within 24 hours following surgery  

The objective of this repository is to reproduce, analyze, and extend the findings of the original study through data exploration, feature analysis, and machine learning modelling.

---

## Research Paper

**Chan et al. (2018)**  
*Combined Assessment of Risk Encountered in Surgery (CARES)*  

The original research paper is included in this repository for reference: `Chan et al 2018.pdf`


## Dataset

The dataset consists of a comprehensive collection of:

- Patient demographics  
- Preoperative clinical assessments  
- Intraoperative variables  
- Postoperative outcome measures  

**Data Source:**  
https://datadryad.org/stash/dataset/doi:10.5061/dryad.v142481#usage  
(Sourced via Google Dataset Search)



---

##  Project Components

### 1️) Data Wrangling & Exploratory Data Analysis  
**File:** `Data Wrangling Chan.ipynb`

- Data cleaning and preprocessing  
- Feature inspection and transformation  
- Handling missing values  
- Exploratory statistical analysis  

---

### 2️) Power BI Analysis  
**File:** `Data Analysis Chan.pbix`

- Visual exploration of surgical risk factors  
- Feature relationships and distribution analysis  
- Clinical trend identification  

---

### 3️) Machine Learning Modelling  
**File:** `ML Modelling Chan.ipynb`

Primary modelling focus:

- Logistic Regression (core predictive model)
- Classification performance evaluation  
- Model comparison and validation  

Evaluation metrics include:

- Accuracy  
- Precision / Recall  
- ROC-AUC  
- Confusion Matrix  

The final Logistic Regression model surpassed the predictive performance reported in the Chan et al. (2018) paper, aligning closely with the original CARES risk framework.

---

### 4️) Full Data Analysis Notebook  
**File:** `CARES.ipynb`

This notebook consolidates:

- Complete EDA  

  
It represents the full analytical depth of the project.

---

##  Objective

The goal of this project is to:

- Reproduce the CARES risk assessment framework  
- Analyze surgical risk factors contributing to critical outcomes  
- Evaluate predictive modelling approaches  
- Explore the potential of machine learning in perioperative risk stratification  

---

## 🛠 Tech Stack

- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- scikit-learn  
- Jupyter Notebook  
- Power BI  

---

##  Disclaimer

This project is for academic and research purposes only.  
It is not intended for clinical decision-making or medical use.
