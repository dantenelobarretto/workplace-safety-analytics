# Workplace Safety Incident Analytics

![Python](https://img.shields.io/badge/Python-3.11-blue)

![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue)

![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)

![License](https://img.shields.io/badge/License-MIT-lightgrey)

![Status](https://img.shields.io/badge/Status-Completed-success)

## Overview

Organizations rely on workplace safety analytics to identify operational risks, reduce workplace incidents, and improve employee well-being. However, access to realistic occupational safety datasets is often limited due to privacy concerns and organizational confidentiality.

This project develops a synthetic workplace safety dataset that simulates employees, workplace incidents, investigations, inspections, corrective actions, and safety performance indicators. Following the CRISP-DM (Cross-Industry Standard Process for Data Mining) methodology, the project demonstrates how synthetic operational data can support exploratory analysis, predictive modeling, and safety decision-making while preserving data privacy.

---

## Project Highlights

• Synthetic workplace safety dataset

• Relational safety data model

• Incident severity prediction

• Operational risk analytics

• CRISP-DM Framework

• End-to-end Python analytics workflow

---

## Business Problem

Organizations must continuously monitor workplace incidents to reduce injuries, improve compliance, and strengthen overall safety performance.

Real workplace safety data is rarely accessible because it contains sensitive employee information and confidential operational records. This limits opportunities for analytics development, employee training, and predictive modeling.

This project addresses these challenges by generating realistic synthetic workplace safety data capable of supporting analytics, reporting, and machine learning applications.

Key challenges addressed include:

- Workplace incident monitoring
- Safety performance evaluation
- Operational risk identification
- Investigation and corrective action tracking
- Synthetic occupational safety data generation

---

## Dataset

This project uses a fully synthetic workplace safety dataset designed to simulate real-world occupational safety operations.

Dataset includes:

- Employee records
- Workplace incidents
- Incident investigations
- Safety inspections
- Corrective actions
- Incident severity
- Department information
- Location and reporting details

The synthetic data preserves realistic operational relationships while ensuring no confidential employee information is exposed.

---

## Methodology

The project follows the CRISP-DM framework.

### Data Generation

- Synthetic employee generation
- Incident simulation
- Relational data modeling
- Operational constraint validation

### Data Preparation

- Data validation
- Missing value handling
- Feature engineering
- Exploratory Data Analysis (EDA)

### Analytics

- Incident trend analysis
- Severity distribution analysis
- Department safety performance
- Operational risk assessment

### Predictive Modeling

- Incident severity prediction
- Classification modeling
- Feature engineering
- Model evaluation

---

## Results

The project successfully generated a realistic workplace safety dataset suitable for analytics, dashboard development, and predictive modeling.

### Key Outcomes

- Developed realistic synthetic workplace safety operations spanning employees, incidents, inspections, and investigations.
- Simulated operational safety risks and corrective actions for organizational safety monitoring.
- Built analytics workflows supporting incident reporting and safety performance evaluation.
- Demonstrated how synthetic safety datasets can enable secure analytics development while protecting employee privacy.

---

## Tech Stack

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Scikit-learn
- Matplotlib

### Development Environment

- Jupyter Notebook

### Methodology

- CRISP-DM

---

## Repository Structure

```
Workplace-Safety-Analytics/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_Data_Generation.ipynb
│   ├── 02_EDA.ipynb
│   ├── 03_Modeling.ipynb
│   └── 04_Evaluation.ipynb
│
├── documentation/
│   └── Workplace Safety Incidents.docx
│
├── figures/
│
├── README.md
│
└── requirements.txt
```

---

## Future Improvements

Potential improvements include:

- Develop time-series forecasting models for workplace incident trends.
- Evaluate anomaly detection techniques for identifying unusual safety incidents.
- Expand simulations to include contractor and visitor safety records.
- Integrate interactive dashboards using Power BI or Streamlit.
- Simulate safety culture indicators and behavioral observations.
- Generate larger-scale synthetic datasets for organizational benchmarking.
- Explore explainable AI techniques to improve model transparency for safety decision-making.
