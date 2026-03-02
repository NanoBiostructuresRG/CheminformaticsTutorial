# Cheminformatics Tutorial
**Version 1.0.0 - February, 2026. Monterrey**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

[![Version](https://img.shields.io/badge/version-v1.0-blue.svg)]()

---

## Description

This tutorial on **Cheminformatics in Drug Discovery** simulates a six-month research workflow, guiding the transition from raw chemical data acquisition to predictive modeling and ligand-based virtual screening of large chemical libraries.

---

## Pedagogical Approach

This tutorial follows a **bottom-up** computational workflow, progressively constructing the pipeline from raw molecular representations to predictive modeling and ligand-based virtual screening.

Pedagogically, it adopts a **project-based learning (PBL)** framework. Learners simulate the responsibilities of a computational chemist within a structured research timeline, developing technical rigor, methodological coherence, and reproducible scientific practice.

---

## Curriculum Overview

### MODULE 1: Data Acquisition & Molecular Representation (Month 1-2)
*Focus: Establishing the digital foundation of chemical matter.*

* **Environment Setup:** Configuration of a reproducible **Google Colab** framework for cheminformatics workflows.
* **Programmatic Access:** Automated data retrieval from **PubChem** and **ChEMBL** using Python APIs.
* **Chemical Notation:** SMILES, InChIKey, and structure file formats (.SDF, .MOL).
* **Chemical Representation and Visualization:** Conversion of molecular encodings into computational objects and 2D structural depictions for inspection and modeling.


### MODULE 2: Feature Engineering & Exploratory Data Analysis (Month 2-3)
*Focus: Quantifying and exploring chemical structure.*

* **Data Curation:** Structural standardization, salt stripping, and tautomer handling with **RDKit**.
* **Molecular Descriptors:** Calculation of key 1D and 2D physicochemical properties (LogP, MW, PSA).
* **Molecular Fingerprints:** Implementation of ECFP4/Morgan fingerprints for similarity and modeling.
* **Exploratory Data Analysis:** Visualization of property distributions and chemical space using Matplotlib and Seaborn.


### MODULE 3: Predictive Modeling (Month 4-5)
*Focus: Learning structure–activity relationships through machine learning.*

* **Model Training:** Supervised learning algorithms such as **Logistic Regression** and **Random Forest**.
* **Model Validation:** Evaluation using ROC-AUC, precision-recall analysis, and cross-validation strategies.
* **Performance Interpretation:** Feature importance and model behavior analysis.
* **Environment Setup:** Configuring VS Code for computational chemistry workflows.


### MODULE 4: Virtual Screening & Implementation (Month 6)
*Focus: Applying predictive models to prioritize candidate compounds.*

* **Ligand-Based Virtual Screening:** Applying trained models to large chemical libraries (e.g., COCONUT or ChEMBL subsets).
* **Candidate Prioritization:** Probability thresholding and filtering strategies.
* **Scientific Reporting:** Preparing reproducible reports and technical summaries.

---

## Purpose
The purpose of this tutorial is to help you:

- **Master Molecular Representation**: Develop a rigorous understanding of how chemical structures are digitized, standardized, and manipulated using computational tools.

- **Implement Automated Workflows**: Transition from manual data handling to automated, programmatic retrieval and curation of chemical data from global databases such as ChEMBL and PubChem.

- **Integrate Chemistry and Machine Learning**: Apply statistical and machine learning methods to model structure–activity relationships and predict biological activity..

- **Perform Ligand-Based Virtual Screening**: Deploy trained models to evaluate and prioritize compounds from large chemical libraries (e.g., COCONUT).

- **Develop Professional Computational Practices**: Simulate the workflow of a computational chemist, emphasizing reproducible code, rigorous validation, and clear scientific reporting..

---

## Repository Structure
```text
├── 00_Environment_Setup/       # Installation
├── 01_Data_Acquisition/        # APIs, SMILES, Data Curation
├── 02_Feature_Engineering/     # 2D Descriptors & Fingerprints
├── 03_Predictive_Modeling/     # Machine Learning & Model Validation
├── 04_Virtual_Screening/       # Ligand-based screening on large libraries
└── 05_Reporting/               # Reproducible analysis & technical reports

```
---

## Requirements
* **Python 3.10+**
* **RDKit** (Cheminformatics engine)
* **Pandas / NumPy** (Data manipulation)
* **Scikit-Learn** (Machine Learning)
* **Matplotlib / Seaborn** (Visualization)

* **Anaconda**
* **environment.yml**

* **VS Code**

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