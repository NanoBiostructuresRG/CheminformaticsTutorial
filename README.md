# Cheminformatics Tutorial
**Version 1.0.0 - February, 2026. Monterrey**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

[![Version](https://img.shields.io/badge/version-v1.0-blue.svg)]()

---

## Description

This tutorial on **Cheminformatics in Drug Discovery** simulates a six-month research workflow, guiding the transitio from raw chemical data acquisition to predictive modeling and virtual screening.

---

## Curriculum Overview

### MODULE 1: Data Acquisition & Molecular Representation (Month 1-2)
*Focus: Establishing the digital foundation of chemical matter.*

* **Chemical Notation:** Systematic understanding of SMILES, InChI, and connection tables (.SDF, .MOL).
* **Programmatic Access:** Automated data retrieval from **ChEMBL** and **PubChem** using Python APIs.
* **Data Curation:** Structural standardization, salt stripping, and tautomer handling via **RDKit**.
* **Environment Setup:** Configuring VS Code for high-throughput chemical scripting.

### MODULE 2: Feature Engineering & Exploratory Data Analysis (Month 2-3)
*Focus: Quantifying chemical structures for computational analysis.*

* **Molecular Descriptors:** Calculation of 1D, 2D, and 3D physicochemical properties (LogP, MW, PSA).
* **Molecular Fingerprints:** Implementation of ECFP4/Morgan fingerprints for similarity assessment.
* **EDA (Exploratory Data Analysis):** Visualizing chemical space and property distributions using Matplotlib and Seaborn.

### MODULE 3: Predictive Modeling & QSAR (Month 4-5)
*Focus: Applying Machine Learning to relate structure to biological activity.*

* **Model Training:** Supervised learning algorithms including **Logistic Regression** and **Random Forest**.
* **Model Validation:** Evaluation through RMSE, $R^2$, and ROC-AUC metrics.
* **QSAR Replication:** Replicating literature-based Quantitative Structure-Activity Relationship (QSAR) models.

### MODULE 4: Virtual Screening & Implementation (Month 6)
*Focus: Applying the pipeline to identify potential drug leads.*

* **Virtual Screening:** Applying trained models to predict activity in commercial or natural product libraries (e.g., **COCONUT**).
* **Ligand Design:** Criteria for hit selection and chemical optimization.
* **Scientific Synthesis:** Summarizing findings into technical reports and research presentations.

---

## Purpose
The purpose of this tutorial is to help you:

- Master Molecular Representation: Develop a rigorous understanding of how chemical structures are digitized, standardized, and manipulated using computational tools.

- Implement Automated Workflows: Transition from manual data handling to automated, programmatic data retrieval and curation from global chemical databases (ChEMBL, PubChem).

- Bridge Chemistry and Data Science: Apply statistical and machine learning methods—specifically QSAR (Quantitative Structure-Activity Relationship)—to predict biological activity and toxicity.

- Execute Virtual Screenings: Design and deploy a full discovery pipeline to identify potential drug leads from massive chemical libraries (e.g., COCONUT).

- Develop Professional Research Skills: Simulate the responsibilities of a computational chemist in a laboratory setting, focusing on reproducible code, rigorous validation, and scientific synthesis of results.

---

## Repository Structure
```text
├── 01_Data_Acquisition/     # APIs, SMILES, and Data Cleaning
├── 02_Feature_Engineering/  # 2D/3D Descriptors & Fingerprints
├── 03_QSAR_Modeling/        # Machine Learning & Model Evaluation
├── 04_Virtual_Screening/    # Application to COCONUT/ZINC libraries
└── 05_Bioinfo_Context/      # Omics and Target Identification

```
---

## Requirements
* **Python 3.10+**
* **RDKit** (Cheminformatics engine)
* **Pandas / NumPy** (Data manipulation)
* **Scikit-Learn** (Machine Learning)
* **Matplotlib / Seaborn** (Visualization)

---

## Author
Developed by **Flavio F. Contreras-Torres** (Tecnológico de Monterrey)      
Monterrey, Mexico - February 2026

---

## Versions     
v.1.0.0 - February 2026. Monterrey, Mexico

---

## License
This project is licensed under the terms of the [MIT License](https://github.com/NanoBiostructuresRG/CheminformaticsTutorial/blob/main/LICENSE).  
See the LICENSE file for full details.