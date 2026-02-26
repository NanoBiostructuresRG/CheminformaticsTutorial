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

# Required Software

- Anaconda Distribution
- VS Code
- Git (optional but recommended)

---

## Step 1 — Install Anaconda

Download and install the **Anaconda Distribution** from:

https://www.anaconda.com/download

Choose the installer for your operating system (Windows / macOS / Linux) and follow the setup instructions.

After installation, open the **Anaconda Prompt** (Windows) or a terminal (macOS/Linux) and verify:

```bash
conda --version
```

If a version number appears, Anaconda is correctly installed.

---

## Step 2 — Create the Course Environment

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

### Step 3 — Register the Environment in Jupyter (Optional but Recommended)

```bash
python -m ipykernel install --user --name cheminf_tutorial --display-name "Python (cheminf_tutorial)"
```

This allows you to select the environment inside Jupyter notebooks.

---

