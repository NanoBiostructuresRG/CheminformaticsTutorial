# Objective

Prepare a reproducible computational environment for the Cheminformatics Tutorial.
This module ensures that all participants work with the same software stack, enabling consistent results and avoiding installation conflicts.

---

# Why This Step Matters

Computational chemistry workflows depend on:
- Controlled software environments
- Specific library versions
- Reproducible installations

Before working with molecular data, we must first establish a stable and standardized environment.

---

# Primary Working Environment

For Modules 1 and 2, JupyterLab will be the main interactive environment.
It allows direct inspection of chemical datasets, visualization of molecular structures, and exploratory data analysis in a clear and intuitive way.

As the course progresses, scripts will complement notebooks to ensure reproducibility and automation.

---

# Required Software

- Anaconda Distribution
- VS Code
- Git (optional but recommended)

---

## Step 1 — Install Anaconda

Download and install the **Anaconda Distribution** (compatible with your operating system) from:

https://www.anaconda.com/download

Choose the installer for your operating system (Windows / macOS / Linux) and follow the setup instructions.

After installation, open the **Anaconda Prompt** (Windows) or a terminal (macOS/Linux) and verify:

```bash
conda --version
```

If a version number appears, Anaconda is correctly installed.

---

## Step 2 — Install VS Code

Download and install VS Code from:

https://code.visualstudio.com/

After installation:
1. Open VS Code
2. Install the following extensions:
    - Python (by Microsoft)
    - Jupyter (by Microsoft)

These extensions enable notebook execution and Python environment management.

---

## Step 3 — Create the Course Environment

From the root directory of this repository, run:

```bash
conda env create -f 00_Environment_Setup/environment.yml
```

Once the installation completes, activate the environment:

```bash
conda activate cheminf_tutorial
```

You should now see `(cheminf_tutorial)` at the beginning of your terminal line.

---

#### Step 4 — Configure VS Code to Use the Environment

- Open the repository folder in VS Code
- Press `Ctrl + Shift + P`
- Select: Python: **Select Interpreter**
- Choose `cheminf_tutorial`

---


### Step 5 — Register the Environment in Jupyter (Optional but Recommended)

```bash
python -m ipykernel install --user --name cheminf_tutorial --display-name "Python (cheminf_tutorial)"
```

This allows you to select the environment inside Jupyter notebooks.

---

### Step 6 — Verify RDKit Installation

Create a new notebook and run:

```bash
from rdkit import Chem
Chem.MolFromSmiles("CCO")
```

If no errors appear, your environment is correctly configured.

---

© 2026 Flavio F. Contreras-Torres — MIT License
