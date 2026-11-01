# Dental Disease Risk Prediction Using Machine Learning

**Bachelor's Thesis in Data Science | Universitat Carlemany**

**Author:** Nazaret Basaldella  
**Field:** Data Science · Machine Learning · Healthcare Analytics  
**Year:** 2026

## Project Overview

This project was developed as part of my Bachelor's Degree in Data Science at Universitat Carlemany.

It explores the application of **Machine Learning to predict dental disease risk**, integrating socioeconomic, demographic, lifestyle, and oral health-related variables.

By combining my background in **Dentistry and Data Science**, this research aims to investigate how predictive analytics can contribute to understanding oral health inequalities, identifying risk factors, and supporting data-driven approaches to preventive healthcare.

The study focuses on the prediction of dental disease, including dental caries and periodontal conditions, using publicly available health survey data.

## Dataset

**Source:** National Health and Nutrition Examination Survey (NHANES), 2011–2012.

NHANES is a nationally representative health survey conducted in the United States, combining demographic, socioeconomic, health-related, and clinical examination data.

The project integrates multiple categories of variables:

- **Demographic factors:** Age, gender, and other population characteristics.
- **Socioeconomic factors:** Income, education, and related indicators.
- **Oral health indicators:** Dental examination findings and oral health-related variables.
- **Lifestyle factors:** Smoking, alcohol consumption, and physical activity.
- **Health-related variables:** Additional indicators potentially associated with oral disease.

The target variable represents the presence or absence of dental disease, incorporating information related to caries and periodontal conditions.

## Methodology

The project follows a structured end-to-end Machine Learning workflow.

### 1. Data Collection and Integration

- Extraction and integration of relevant NHANES datasets.
- Selection of demographic, socioeconomic, lifestyle, and oral health variables.
- Construction of the analytical dataset.

### 2. Data Preprocessing

- Identification and treatment of missing values.
- Median imputation for numerical variables, including age and income-related indicators.
- Mode imputation for categorical variables.
- Encoding of categorical features.
- Feature standardization using `StandardScaler`.
- Stratified training and testing split (80% / 20%).
- Consideration of class imbalance during model development.

### 3. Exploratory Data Analysis (EDA)

Exploratory analysis was performed to investigate:

- Population characteristics and socioeconomic distributions.
- Dental disease prevalence.
- Relationships between oral health outcomes and socioeconomic factors.
- Associations between lifestyle behaviors and dental disease.
- Distribution and quality of predictive variables.

### 4. Machine Learning Models

Different supervised classification algorithms were explored and compared:

- **Logistic Regression**
- **Random Forest**

These models were selected to compare interpretable statistical approaches with more complex nonlinear Machine Learning techniques.

Class-weight balancing strategies were also considered to address unequal class distributions.

### 5. Model Evaluation

Model performance was assessed using several classification metrics:

| Metric | Purpose |
|---|---|
| Accuracy | Overall classification performance |
| Precision | Reliability of positive predictions |
| Recall | Ability to identify individuals with dental disease |
| F1-score | Balance between precision and recall |
| ROC-AUC | Ability to distinguish between outcome classes |
| Confusion Matrix | Analysis of correct and incorrect classifications |

Special attention was given to **recall and class imbalance**, since failing to identify individuals potentially affected by dental disease represents an important limitation in healthcare-related predictive applications.

## Interactive Dashboard — Power BI

An interactive **Power BI dashboard** was developed to communicate the findings and facilitate the interpretation of the analytical results.

The dashboard provides visual exploration of:

- Population and demographic characteristics.
- Socioeconomic indicators.
- Dental disease prevalence.
- Relationships between risk factors and oral health outcomes.
- Classification performance metrics.
- Confusion matrix and ROC curve analysis.

The dashboard complements the Python-based analysis by transforming statistical and predictive results into accessible visual insights.

## Technologies and Tools

**Programming and Data Analysis**
- Python
- Pandas
- NumPy
- Jupyter Notebook

**Machine Learning**
- Scikit-learn
- XGBoost

**Data Visualization**
- Matplotlib
- Seaborn
- Power BI

**Development and Version Control**
- Git
- GitHub

## Research Objectives

The main objectives of this research are:

1. Investigate associations between socioeconomic, demographic, and behavioral factors and dental disease.
2. Develop classification models capable of estimating dental disease risk.
3. Compare different Machine Learning algorithms using standardized evaluation metrics.
4. Assess the challenges of imbalanced healthcare datasets.
5. Explore the potential of predictive analytics as a complementary tool for oral health research and prevention.

## Limitations and Future Work

Several limitations must be considered when interpreting the findings:

- The cross-sectional nature of NHANES limits causal interpretation.
- Class imbalance may affect sensitivity to positive cases.
- Survey data may contain missing values and measurement limitations.
- Model performance on an independent external population has not been established.
- Predictive associations do not necessarily imply causal relationships.

Future developments could include:

- Validation using additional NHANES survey cycles.
- External validation with independent clinical datasets.
- Advanced feature selection and model explainability techniques.
- Further optimization of classification thresholds.
- Exploration of longitudinal data and clinical decision-support applications.

## Academic Documentation

The repository includes the supporting materials developed for the Bachelor's Thesis:

- **Source Code:** Python scripts and Machine Learning implementation.
- **Jupyter Notebooks:** Data preprocessing, exploratory analysis, model training, and evaluation.
- **Power BI Dashboard:** Interactive visualization of analytical findings.
- **Bachelor's Thesis:** Full academic research document.
- **Thesis Presentation:** Slides prepared for the final academic defense.
- **Appendices:** Supplementary documentation and supporting materials.

## Research Perspective

This project represents the intersection of two professional disciplines: **Dentistry and Data Science**.

It reflects my interest in applying statistical analysis, Machine Learning, and data visualization to healthcare challenges, with a particular focus on preventive medicine, population health, and evidence-based decision-making.

The predictive models are intended for research and exploratory analysis and are not validated for clinical diagnosis or independent medical decision-making.

---

**Developed by Nazaret Basaldella**  
*Bachelor's Degree in Data Science — Universitat Carlemany*  
*Background in Dentistry | Interested in Healthcare Data Science, Machine Learning and Predictive Analytics*
