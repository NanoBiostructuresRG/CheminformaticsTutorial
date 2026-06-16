# Cheminformatics Tutorial
**Version 1.0 - June, 2026. Monterrey**

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

* **Platform Setup:** Configuration of a reproducible working environment using **Google Colab**, **Jupyter**, **Anaconda**, and **VS Code**.


### MODULE 1: Molecular Data Acquisition and Representation
*Focus: Establishing the digital foundation of chemical matter.*

* **Programmatic Access:** Automated data retrieval from **PubChem** and **ChEMBL** using Python APIs.
* **Chemical Notation:** Introduction to SMILES, InChI, InChIKey, and common structure file formats sucha as SDF and MOL.
* **Molecular Representation:** Conversion of chemical encodings into computational molecular objects for downstream analysis.
* **Chemical Visualization:** Generation of 2D molecular depictions for structural inspection and interpretation.


### MODULE 2: Data Curation & Structural Exploration
*Focus: Preparing chemically consistent datasets for analysis and modeling.*

* **Data Curation:** Structural standardization, salt stripping, tautomer handling, stereochemistry normalization, and duplicate removal using RDKit.
* **Structure-level EDA:** Inspection of duplicate entries, scaffold diversity, atom composition, molecular size trends, and class balance.
* **Chemical Quality Control:** Identification of inconsistent structures, missing values, and dataset-level issues that may affect downstream analysis.
* **Preliminary Chemical Space Inspection:** Early visualization of structural diversity and dataset composition prior to descriptor generation.


### MODULE 3: Molecular Descriptors, Fingerprints & Feature Engineering
*Focus: Transforming chemical structures into machine-readable features.*

* **Molecular Descriptors:** Calculation of key 1D and 2D physicochemical properties, including molecular weight (MW), LogP, TPSA, HBD, HBA, and rotatable bonds.
* **Descriptor-Based EDA:** Distribution analysis of calculated properties, correlation assessment, outlier detection, and redundancy evaluation.
* **Molecular Fingerprints:** Generation of structural fingerprints for similarity analysis, diversity assessment, and machine learning applications.
* **Feature Engineering:** Preparation and organization of descriptor matrices and fingerprint-based representations for predictive modeling.
* **Chemical Space Visualization:** Use of methods such as PCA for preliminary visualization of descriptor-based chemical space.


### MODULE 4: Predictive Modeling
*Focus: Learning structure–activity relationships through machine learning.*

* **Model Inputs:** Use of molecular descriptors and fingerprint matrices as representations for classification tasks.
* **Model Training:** Supervised learning algorithms such as **Logistic Regression** and **Random Forest** for bioactivity prediction.
* **Model Validation:** Evaluation using ROC-AUC, precision-recall analysis, and cross-validation strategies.
* **Performance Interpretation:** Analysis of model behavior, feature importance, and predictive limitations.
* **Structure–Activity Learning:** Introduction to computational strategies for relating molecular features to biological activity outcomes.


### MODULE 5: Virtual Screening & Scientific Implementation
*Focus: Applying predictive models to prioritize candidate compounds.*

* **Ligand-Based Virtual Screening:** Application of trained models to large chemical libraries such as COCONUT or selected ChEMBL subsets.
* **Candidate Prioritization:** Probability thresholding, ranking, and filtering strategies for hit selection.
* **Result Interpretation:** Evaluation of screened compounds in terms of confidence, diversity, and practical relevance.
* **Scientific Reporting:** Preparation of technical summaries, screening reports, and structured outputs for scientific communication.


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
├── 01_Data_Acquisition/        # APIs, SMILES, InCHI, SDF/MOL 
├── 02_Data_Curation/           # Data Curation, structural EDA
├── 03_Feature_Engineering/     # Fingerprints, descriptor-based EDA
├── 04_Predictive_Modeling/     # Machine Learning, validation, prediction
├── 05_Virtual_Screening/       # Ligand-based screening, identification, priorization
└── 06_Reporting/               # Technical reports

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

**Authors:** [Flavio F. Contreras-Torres](https://orcid.org/0000-0003-2375-131X). 
Tecnológico de Monterrey.     
Monterrey, Mexico

**Contributors:** [Fernanda I. Saldivar-González](https://orcid.org/0000-0002-0435-8662). 
Tecnológico de Monterrey.     
Monterrey, Mexico


---

## Versions     
v.1.0 - June 2026

---

## License
The content of this tutorial itself is licensed under the terms and conditions of the [Creative Commons Attribution (CC BY 4.0) license](https://creativecommons.org/licenses/by/4.0/legalcode.en), and the underlying source code used to format and display that content is licensed under the [MIT License](https://github.com/NanoBiostructuresRG/CheminformaticsTutorial/blob/main/LICENSE). See the LICENSE file for full details.

### Attribution
If you use or adapt this material, please provide appropriate credit to the original [authors](https://orcid.org/my-orcid?orcid=0000-0003-2375-131X) and repository:
[https://github.com/NanoBiostructuresRG](https://github.com/NanoBiostructuresRG)


