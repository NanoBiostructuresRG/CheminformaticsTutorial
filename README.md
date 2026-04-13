# Cheminformatics Tutorial
**Version 1.0.0 - February, 2026. Monterrey**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

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

### MODULE 0: Environment Setup
*Focus: Preparing a reproducible computational environment for cheminformatics workflows.*

* **Installation:** Setup of reproducible cheminformatics workflows in **Google Colab**, **Anaconda**, and **VS Code**.


### MODULE 1: Molecular Data Acquisition and Representation (Month 1-2)
*Focus: Establishing the digital foundation of chemical matter.*

* **Programmatic Access:** Automated data retrieval from **PubChem** and **ChEMBL** using Python APIs.
* **Chemical Notation:** SMILES, InChIKey, and structure file formats (.SDF, .MOL).
* **Chemical Representation and Visualization:** Conversion of molecular encodings into computational objects and 2D structural depictions for inspection and modeling.


### MODULE 2: Exploratory Data Analysis & Feature Engineering (Month 2-3)
*Focus: Quantifying and exploring chemical structure.*

* **Data Curation:** Structural standardization, salt stripping, tautomer handling, stereochemistry normalization, and duplicate removal using RDKit.
* **Exploratory Data Analysis (EDA)** 
    * **Structural EDA (Pre-descriptor):** Duplicate detection, scaffold diversity inspection, molecular weight distribution (basic calculation), atom composition analysis, and class balance evaluation.
    * **Descriptor-Based EDA (Post-descriptor):** Distribution analysis of calculated properties, correlation assessment (LogP, MW, TPSA, HBD, HBA), outlier detection, PCA-based preliminary chemical space visualization, and property-driven clustering exploration.
* **Molecular Descriptors:** Calculation of key 1D and 2D physicochemical properties (LogP, MW, TPSA, HBD, HBA, rotatable bonds) and evaluation of descriptor redundancy.
* **Molecular Fingerprints:** Implementation of molecular fingerprints for similarity analysis, structural diversity assessment, and machine learning preparation.


### MODULE 3: Predictive Modeling (Month 4-5)
*Focus: Learning structure–activity relationships through machine learning.*

* **Model Training:** Supervised learning algorithms such as **Logistic Regression** and **Random Forest**.
* **Model Validation:** Evaluation using ROC-AUC, precision-recall analysis, and cross-validation strategies.
* **Performance Interpretation:** Feature importance and model behavior analysis.


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
├── 01_Data_Acquisition/        # APIs, SMILES 
├── 02_Feature_Engineering/     # Data Curation, Descriptors & Fingerprints
├── 03_Predictive_Modeling/     # Machine Learning & Model Validation
├── 04_Virtual_Screening/       # Ligand-based Screening on Large Libraries
└── 05_Reporting/               # Reproducible Analysis & Technical Reports

```
---

## Requirements
- **Anaconda**
- **Python 3.10+**
- **RDKit** (Cheminformatics engine)
- **Pandas / NumPy** (Data manipulation)
- **Scikit-Learn** (Machine Learning)
- **Matplotlib / Seaborn** (Visualization)
- **VS Code** (IDE)
- **MiKTex-XeTeX** (Documentation)
- **environment.yml**

---


## Authors
**Flavio F. Contreras-Torres**  
Tecnológico de Monterrey     
Monterrey, Mexico       

---

## Versions     
v.1.0.0 - February 2026

---

## License
The content of this tutorial itself is licensed under the terms and conditions of the [Creative Commons Attribution (CC BY 4.0) license](https://creativecommons.org/licenses/by/4.0/legalcode.en), and the underlying source code used to format and display that content is licensed under the [MIT License](https://github.com/NanoBiostructuresRG/CheminformaticsTutorial/blob/main/LICENSE). See the LICENSE file for full details.

## Attribution
If you use or adapt this material, please provide appropriate credit to the original authors and repository:

> NanoBiostructures Research Group  
> GitHub: https://github.com/NanoBiostructuresRG

