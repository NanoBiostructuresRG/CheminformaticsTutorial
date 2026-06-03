# Module 1: Molecular Data Acquisition and Representation

### Timeline: 
Month 1  (17 - 26 hours)

### Focus: 
Establishing the digital foundation of chemical data through retrieval, organization, and molecular representation.

---

## Contents

Four notebooks:

1. **PubChem Data Retrieval**. Introduction to programmatic chemical data acquisition using the PubChem REST API.
2. **PUG-REST POST Requests**. Structure-based querying with SMILES strings and SDF inputs, including flexible and complex PubChem requests.
3. **ChEMBL Data Retrieval**. Retrieval of target-centered bioactivity data, including molecules, activities, assays, and biological targets.
4. **Molecular Representation and Visualization**. Conversion of encoded molecular records into computational objects and 2D structural depictions for direct chemical interpretation.

---

## Objective

This module introduces the fundamental concepts required to **retrieve, organize, and represent chemical data** in a computational workflow.

By the end of this module, you will understand how chemical structures are encoded digitally, how molecular information can be retrieved from public databases, and how structured molecular records can be transformed into visually interpretable chemical representations.

---

## Learning Outcomes

After completing this module, you will be able to:

- Retrieve chemical data programmatically from **PubChem** and **ChEMBL**.
- Perform structure-based queries using PubChem PUG-REST POST requests.
- Interpret and manipulate molecular representations (`SMILES`, `InChIKey`).
- Work with common structure file formats (`.SDF`, `.MOL`).
- Compare structural and metadata differences between public chemical databases.
- Connect target, assay, activity, and molecular records into structured datasets.
- Render 2D molecular structures from encoded chemical representations.

---

## Core Topics

1. Programmatic Data Access
    - Introduction to PubChem REST API
    - Introduction to ChEMBL API
    - Data parsing and format differences
    - Structure-based queries with POST requests

2. Chemical Notation
    - SMILES and canonical SMILES
    - InChI and InChIKey
    - Structure file formats (.SDF, .MOL)

3. Molecular Representation and Visualization
    - Converting encoded records into molecular objects
    - Rendering 2D molecular depictions
    - Structural inspection of retrieved compounds

---

## Module Structure

```text
01_Data_Acquisition/
│
├── README.md
├── scripts/        # Reproducible data retrieval and curation scripts
├── notebooks/      # Interactive exploration and demonstrations
└── data_raw/       # Raw downloaded files and datasets
```

---

## Expected Output

By the end of this module, you should produce:

- A raw dataset retrieved from PubCHem
- At least one structure-based query workflow using POST requests
- A structured ChEMBL bioactivity dataset
- A set of representative 2D molecular visualizations
- An enriched structural file such as .SDF


These outputs will serve as the foundation for Module 2: Data Curation and Structural Exploration.

---

## Conceptual Position in the Workflow

This module represents the entry point of the computational pipeline. It establishes the molecular records, identifiers, and structural representations that will later be curated, explored, and analyzed in downstream modules.

---

## License
The content of this tutorial itself is licensed under the terms and conditions of the [Creative Commons Attribution (CC BY 4.0) license](https://creativecommons.org/licenses/by/4.0/legalcode.en), and the underlying source code used to format and display that content is licensed under the [MIT License](https://github.com/NanoBiostructuresRG/CheminformaticsTutorial/blob/main/LICENSE). See the LICENSE file for full details.


