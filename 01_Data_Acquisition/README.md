# Module 1: Data Acquisition & Molecular Representation

### Timeline: 
Month 1–2

### Focus: 
Establishing the digital foundation of chemical data

---

# Objective

This module introduces the fundamental concepts required to represent, retrieve, and curate chemical data in a computational workflow.

By the end of this module, you will understand how chemical structures are encoded digitally and how to construct a clean, analysis-ready molecular dataset from public chemical databases.

---

# Learning Outcomes

After completing this module, you will be able to:

- Interpret and manipulate molecular representations (SMILES, InChI).
- Work with common structure file formats (.SDF, .MOL).
- Retrieve chemical data programmatically from **PubChem** and **ChEMBL**.
- Compare structural and metadata differences between databases.
- Apply structural standardization techniques using **RDKit**.
- Generate a curated dataset ready for feature engineering.

---

# Core Topics
1. Chemical Notation
    - SMILES and canonical SMILES
    - InChI and InChIKey
    - Structure file formats (.SDF, .MOL)

2. Programmatic Data Access
    - Introduction to PubChem REST API
    - Introduction to ChEMBL API
    - Data parsing and format differences

3. Data Curation with RDKit
    - Structure validation
    - Salt removal
    - Standardization
    - Tautomer handling
    - Removing duplicates

---

# Module Structure

```text
01_Data_Acquisition/
│
├── README.md
├── scripts/        # Reproducible data retrieval and curation scripts
├── notebooks/      # Interactive exploration and demonstrations
└── data_raw/       # Raw downloaded datasets
```

---

# Expected Output

By the end of this module, you should produce:

- A raw dataset retrieved from PubCHem
- A raw dataset retrieved from ChEMBL
- A curated molecular dataset (e.g., `curated_dataset.csv`)
    - Standardized SMILES representations
    - Clean molecular identifiers
    - Remotion of duplicates, salts, etc. 

These datasets will serve as the structural foundation for subsequent modules.

---

# Conceptual Position in the Workflow

This module represents the bottom-up starting point of the computational pipeline.
All subsequent modeling and screening tasks depend on the structural integrity and correctness of the dataset constructed here.

---

© 2026 Flavio F. Contreras-Torres — MIT License