# Machine Learning Approach to Early Nutrition-Risk Prediction in Geriatric ICU Care for Older Adults Using MIMIC-III Structured Data  
**UT Austin MSAI — AI in Healthcare | Assignment 4: Self-Learning Tutorial**

## Overview
This repository contains self-learning tutorial project for the **AI in Healthcare** course in the **M.S. in Artificial Intelligence (MSAI)** program at The University of Texas at Austin.

The main work for this project is provided in the **Jupyter/Colab notebook uploaded in this repository**.  
The notebook presents an end-to-end workflow for:

- cohort extraction from **MIMIC-III**
- early feature engineering from the **first 24 hours of ICU stay**
- construction of a **PNI-style nutrition-risk proxy**
- leakage-aware machine learning modeling
- comparison of **Logistic Regression** and **XGBoost**
- model interpretation using **SHAP**
- extension analysis for **30-day mortality**

## Main File
Please refer to the notebook file in this repository for the full implementation, results, and explanations.

> This repository is primarily notebook-based.  
> The uploaded notebook is the main source of code, methodology, and outputs for this assignment.

## Project Scope
This work focuses on **older adult ICU patients (age ≥ 65)** using **structured MIMIC-III data**.  
The goal is to build a **reproducible educational workflow** for early nutrition-risk prediction and interpretation, rather than a production-grade clinical prediction system.

## Important Access and Usage Notes

### 1. MIMIC-III access restriction
This project uses **MIMIC-III**, which is a restricted-access clinical dataset.  
To reproduce the full workflow, users must have:

- approved access to **MIMIC-III**
- required credentialing / training
- valid access to the appropriate **Google BigQuery** environment
- a properly configured **Google Colab** or Python environment

Because of these restrictions, this repository does **not** provide raw patient data.

Please use this material in a way that is consistent with:
- course policies
- academic integrity expectations
- dataset usage agreements
- responsible research practice

### 2. No clinical deployment
This notebook is intended for **educational and research demonstration purposes only**.  
It is **not** a validated clinical decision-support tool and should **not** be used for direct patient care or clinical deployment.

## Reproducibility Notes
Results may vary slightly across reruns due to:
- random initialization
- package or software versions
- execution environment differences
- differences in available credentials / data access setup

## Disclaimer
This repository contains deidentified-data workflow logic only.  
All work should be conducted in accordance with relevant **data use agreements, ethical requirements, and credentialing rules**.

## Author
Prepared as part of the **UT Austin MSAI — AI in Healthcare** coursework.
