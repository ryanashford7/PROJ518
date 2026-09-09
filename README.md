# Predicting Alzheimer's Disease Progression Using Blood-Based Biomarkers

## Overview

This repository contains the Python code developed for an MSc dissertation investigating the use of blood-based biomarkers for predicting progression to Alzheimer's disease (AD) using longitudinal survival analysis.

The study evaluates whether plasma biomarkers provide additional prognostic information beyond baseline clinical diagnosis, with particular emphasis on plasma phosphorylated tau 217 (p-tau217).

Cox proportional hazards and Random Survival Forest (RSF) models were used to evaluate time to AD conversion and compare the predictive performance of different biomarker configurations.

## Study Objectives

The analysis investigates:

- Whether p-tau217 improves prediction of AD progression beyond baseline clinical diagnosis.
- Whether additional blood-based biomarkers provide further predictive benefit.
- Whether increased model complexity improves prognostic performance.
- The effect of removing p-tau217 on model discrimination and overall prediction accuracy.

## Biomarkers

The blood-based biomarkers evaluated were:

- Plasma phosphorylated tau 217 (p-tau217)
- Neurofilament light chain (NfL)
- Glial fibrillary acidic protein (GFAP)
- Amyloid-beta 42/40 ratio (Aβ42/40)

## Analysis

The repository contains code used for:

- Data preprocessing and integration
- Construction of longitudinal time-to-event outcomes
- Cox proportional hazards modelling
- Random Survival Forest modelling
- Cross-validation and C-index evaluation
- Model calibration
- Bootstrap analysis of change in C-index
- Biomarker-removal sensitivity analysis
- Integrated Brier Score (IBS) evaluation
- Generation of figures and results used in the dissertation

## Data Source

Data used in this study were obtained from the Alzheimer's Disease Neuroimaging Initiative (ADNI).

The analytical dataset was constructed by integrating multiple participant-level ADNI datasets containing demographic, clinical, longitudinal diagnostic and plasma biomarker information.

### Data Availability

ADNI data are not included in this repository.

Access to ADNI data is subject to the ADNI Data Use Agreement and must be obtained independently through the Alzheimer's Disease Neuroimaging Initiative.

The code provided in this repository is intended to document the analytical methods used in the dissertation and support reproducibility where appropriate ADNI data access has been obtained.

## Software

The analysis was conducted in Python. Principal packages included:

- NumPy
- pandas
- Matplotlib
- Seaborn
- scikit-learn
- lifelines
- scikit-survival

## Repository Structure

The analysis code is provided in the accompanying Python notebook/script(s).

Further information about individual files will be added as the repository is finalised.

## Author

Ryan Ashford  
MSc Health Data Science and Statistics  
University of Plymouth

## Academic Use

This repository accompanies an MSc dissertation submitted to the University of Plymouth.

The repository contains analytical code only and does not redistribute ADNI participant data.
