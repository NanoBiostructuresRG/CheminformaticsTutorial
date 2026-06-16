---
title: Cheminformatics Tutorial
layout: default
---

<!--This line is commented-->
<img src="assets/cheminfo_logo.svg" alt="logo" style="float: right; width: 160px; margin-left: 20px;">


## Cheminformatics Tutorial
 
Cheminformatics focuses on how chemical structures are represented, curated, analyzed, and used to support computational decisions. This tutorial introduces a reproducible workflow that begins with molecular data acquisition and ends with predictive modeling and ligand-based virtual screening.

Participants will learn how to retrieve molecular records from public databases such as PubChem and ChEMBL, represent structures using formats such as SMILES, InChI, InChIKey, SDF, and MOL, and convert these records into molecular objects for analysis. The tutorial also addresses common issues found in real datasets, including salts, duplicate entries, inconsistent structures, missing information, stereochemical ambiguity, and differences between database records and usable molecular structures.

After data acquisition, the tutorial moves into curation, structural exploration, molecular descriptors, fingerprints, and feature engineering. These steps allow users to transform curated molecular collections into numerical representations that can be used to compare compounds, evaluate diversity, detect outliers, assess descriptor redundancy, visualize chemical space, and prepare data for machine learning.

**[HDDFlyzer](https://github.com/NanoBiostructuresRG/hddflyzer)** is introduced as a tool for reproducible exploration of high-dimensional molecular descriptor spaces. Within the tutorial, it supports the analysis of curated molecular collections through descriptor tables, similarity relationships, dimensionality reduction, visualization, and traceable output files. Its role is to help users inspect the structure, diversity, and organization of chemical libraries before applying predictive modeling or virtual screening strategies.

The final modules focus on supervised learning and ligand-based virtual screening. Users will train and evaluate models using descriptor and fingerprint matrices, interpret performance metrics and model limitations, and apply trained models to prioritize candidate compounds from larger chemical libraries.

This tutorial is intended for learners who need a practical and conceptually grounded introduction to cheminformatics workflows. At the end of each module, participants will complete a project to demonstrate their understanding of the concepts, tools, and interpretation strategies developed during the training.

---

### Contents:
#### Module 0. Environment Setup
1. Programmatic Access
2. Chemical Notation
3. Molecular Representation
4. Chemical Visualization 

#### Module 1. Molecular Data Acquisition and Representation 
1. Data Curation
2. Structure-level EDA 
3. Chemical Quality Control    
4. Preliminary Chemical Space Inspection
5. [End-of-Module 1](https://nanobiostructuresrg.github.io/CheminformaticsTutorial/modules/end-of-modules/m1_final_project.pdf)

#### Module 2: Data Curation & Structural Exploration


#### Module 3: Molecular Descriptors, Fingerprints & Feature Engineering


#### Module 4: Predictive Modeling


#### Module 5: Virtual Screening & Scientific Implementation


---

### Downloads
- **[Tutorial PDF](https://nanobiostructuresrg.github.io/CheminformaticsTutorial/tutorial/CheminformaticsTutorial.pdf)**. This is the most up-to-date version of the tutorial and may continue to receive minor revisions, including the correction of typographical errors and other small improvements.


### Assessment Notebooks

To complete the training and obtain credit, participants are required to engage with the tutorial materials in the prescribed sequence and to complete mandatory assessment notebooks:

- **[Computational Workspace](https://nbviewer.org/github/NanoBiostructuresRG/CheminformaticsTutorial/blob/main/modules/m0_environment_setup/notebooks/00_installation.ipynb)**
- **[Pubchem Data Retrieval](https://nbviewer.org/github/NanoBiostructuresRG/CheminformaticsTutorial/blob/main/modules/m1_data_acquisition/notebooks/01_pubchem_data_retrieval.ipynb)**
- **[PUG-REST and HTTP-POST Requests](https://nbviewer.org/github/NanoBiostructuresRG/CheminformaticsTutorial/blob/main/modules/m1_data_acquisition/notebooks/02_pugrest_post_requests.ipynb)**
- **[ChEMBL Data Retrieval](https://nbviewer.org/github/NanoBiostructuresRG/CheminformaticsTutorial/blob/main/modules/m1_data_acquisition/notebooks/03_chembl_data_retrieval.ipynb)**
- **[Molecular Representation & Visualization](https://nbviewer.org/github/NanoBiostructuresRG/CheminformaticsTutorial/blob/main/modules/m1_data_acquisition/notebooks/04_molecular_representation.ipynb)**
- **[Protein Data Acquisition from PDB](https://nbviewer.org/github/NanoBiostructuresRG/CheminformaticsTutorial/blob/main/modules/m1_data_acquisition/notebooks/05_protein_data_acquisition_from_PDB.ipynb)**


---

### License & Attribution  
The content of this tutorial itself is licensed under the terms and conditions of the [Creative Commons Attribution (CC BY 4.0) license](https://creativecommons.org/licenses/by/4.0/legalcode.en), and the underlying source code used to format and display that content is licensed under the [MIT license](https://github.com/NanoBiostructuresRG/AutodockTutorial/blob/main/LICENSE). See the LICENSE files for full details.

If you use or adapt this material, please provide appropriate credit to the original author, [FFCT](https://orcid.org/0000-0003-2375-131X), as well as to the [repository](https://github.com/NanoBiostructuresRG).

---

<div style="display:flex; justify-content:space-between; align-items:center;">
  <span>Version 1.0 — June 2026</span>
  <a href="https://nanobiostructuresrg.github.io/">Back to Main Site</a>
</div>
