
\begin{figure}[h]
\centering
\includegraphics[width=0.51\textwidth]{../../images/logo-tec.png}
\end{figure}


# Final Project – Module 1  
### From Data Retrieval to a Research-Ready Chemical Library

**Version 1.0.0 - February, 2026. Monterrey**  
**Author:** Flavio F. Contreras-Torres. Tecnológico de Monterrey.


--- 

## Project Overview

This final project integrates the four notebooks developed throughout Module 1 into a unified research workflow. The objective is to transform raw molecular data retrieved from public databases into a curated, interpretable, and modeling-ready chemical library.

You will assume the role of a Computational Chemist responsible for delivering a scientifically reliable dataset for a defined biological target. The emphasis is not only on technical execution, but on understanding how data acquisition, curation, structural inspection, and physicochemical reasoning converge to produce research-grade chemical knowledge.



### Project Estimation & Effort Breakdown

| Project Phase | Estimated Time | Difficulty Level | Why does it take this long? |
| :--- | :--- | :--- | :--- |
| **1. Selection & Extraction** | 2 - 3 hours | Medium | Selecting the biological target and navigating ChEMBL/PubChem IDs to ensure the API returns the desired data. |
| **2. Cleaning & Standardization** | 3 - 4 hours | High | The most critical stage. Converting units, handling duplicates, and creating the activity labels often requires multiple code "refinements." |
| **3. Analysis & Visualization** | 2 - 3 hours | Medium | If previous notebooks are understood, this is mostly adapting existing plotting code to the new dataset. |
| **4. Interpretation & Reporting** | 3 - 5 hours | High | This is where the student must think critically. Inspecting molecules and drafting SAR hypotheses requires careful observation. |


> **Notice:** This project is designed to be completed in approximately **10 - 15 hours**.



### **Student Checklist for Success**

To ensure you complete the project within this timeframe, consider the following:

* **Start Simple:** Choose a well-studied target (e.g., Acetylcholinesterase, EGFR, or Mpro) to ensure plenty of data is available.
* **Reusable Code:** Leverage the functions and logic you built in Notebooks 1 through 4.
* **The 80/20 Rule:** Focus on getting a clean, functional dataset first; you can refine the visual styling of your plots later.

---

## Research Question

**How can raw molecular data retrieved from public databases be systematically transformed into a reliable, balanced, and modeling-ready chemical library for a specific biological target?**



## Project Objectives

1. **Programmatic Retrieval:** Extract structural data from PubChem using REST API queries.
2. **Advanced Structural Querying:** Implement structure-based searches using POST requests and similarity logic.
3. **Bioactivity Standardization:** Retrieve and refine ChEMBL activity data for a selected target, ensuring unit consistency.
4. **Dataset Engineering:** Construct an ML-ready dataset with standardized potency (IC₅₀ → pIC₅₀) and binary activity labels.
5. **Structural & Physicochemical Audit:** Evaluate dataset quality through statistical profiling and molecular visualization.
6. **Preliminary SAR Analysis:** Identify qualitative structure–activity trends and scaffold-level patterns.



## Project Workflow

### Phase 1 – PubChem Data Acquisition  
Build an initial molecular dataset through REST API queries. Retrieve structural identifiers (SMILES, InChIKey) and computed physicochemical properties. Evaluate dataset integrity by inspecting missing values, duplicates, and descriptor coverage.

### Phase 2 – Structure-Based Querying (POST Logic)  
Perform at least one structure-driven search (similarity or substructure) using POST requests. Demonstrate technical understanding of GET vs POST communication and document how structural payloads differ from simple textual queries.

### Phase 3 – ChEMBL Bioactivity Extraction and Refinement  
Select a biological target (e.g., PPARγ, Mpro, GPCR, enzyme of interest). Retrieve experimental bioactivity data (IC₅₀, Kᵢ, etc.) and standardize all values to nanomolar (nM).
Generate a binary classification label using a justified potency threshold (e.g., 1,000 nM or $pIC_{50} = 6.0$).  
Export:

- A cleaned ML-ready CSV dataset
- An enriched SDF file embedding structural and bioactivity metadata  

### Phase 4 – Visual Analytics and Structural Audit  
Perform a scientific validation of the curated dataset through:

- Statistical profiling (class balance and log-scale IC₅₀ / pIC₅₀ distribution)
- Physicochemical comparison (MW, AlogP, TPSA)
- Two-dimensional structural visualization of representative compounds

Interpret at least three qualitative SAR observations linking molecular architecture to observed potency trends.



## Required Deliverables

1. Final ML-ready dataset (CSV format).
2. Enriched SDF file containing structural and bioactivity metadata.
3. Structured analytical report (Markdown within notebook) including:
   - Dataset size before and after filtering
   - Data health assessment (missing values and duplicates)
   - Class distribution summary
   - At least three scaffold-level SAR observations
4. Visual dashboard including:
   - Class balance plot
   - Log IC₅₀ / pIC₅₀ histogram
   - One physicochemical comparison plot
   - Structural grid visualization



## Evaluation Criteria

- **Reproducibility:** The workflow runs from raw retrieval to final export without undocumented manual intervention.
- **Data Integrity:** Transparent filtering logic, consistent units, and explicit handling of anomalies.
- **Scientific Reasoning:** Ability to connect structural motifs with physicochemical properties and potency.
- **Technical Clarity:** Clean code, labeled figures, and concise scientific interpretation.



## Expected Outcome

By the end of this project, you will have constructed a curated and chemically interpretable dataset derived entirely through reproducible computational methods. This library will serve as the digital foundation for Module 2: Feature Engineering and Chemical Space Modeling, where molecular representations transition from structural form to quantitative descriptors and predictive learning.



## Recommended Friendly Targets – Metabolic Disorders Context

The following protein targets are strongly associated with obesity, insulin resistance, and metabolic syndrome. They are recommended due to their biological relevance, availability of bioactivity data in ChEMBL, and suitability for structure–activity analysis.

| Target Protein | Biological Role in Metabolic Disorders | Pedagogical Justification |
|---------------|------------------------------------------|---------------------------|
| **DPP-4 (Dipeptidyl Peptidase-4)** | Regulates incretin hormones (GLP-1), directly linked to glucose homeostasis and type 2 diabetes. | Large and clean IC₅₀ datasets in ChEMBL; well-characterized inhibitor scaffolds; ideal for binary classification and SAR visualization. |
| **11β-HSD1 (11-beta-hydroxysteroid dehydrogenase type 1)** | Controls intracellular glucocorticoid activation; associated with visceral obesity and metabolic syndrome. | Moderate-to-large dataset size; structurally diverse inhibitors; excellent for exploring lipophilicity–potency relationships. |
| **AMPK (AMP-activated protein kinase)** | Master regulator of cellular energy balance and metabolic adaptation. | Strong metabolic relevance; provides mechanistic depth; good diversity of activators and modulators for comparative profiling. |
| **ACC1 (Acetyl-CoA Carboxylase 1)** | Key enzyme in fatty acid biosynthesis; implicated in lipid accumulation and obesity. | Enzyme target with measurable IC₅₀ values; useful for metabolic pathway discussion and structure–function reasoning. |
| **FASN (Fatty Acid Synthase)** | Catalyzes de novo lipogenesis; overactive in obesity and metabolic dysregulation. | Abundant inhibitor data; clear biochemical endpoint; suitable for potency standardization and physicochemical profiling exercises. |



### Recommendation

For maximum dataset stability and smoother workflow execution, **DPP-4** and **11β-HSD1** are the most pedagogically robust alternatives.

---

### License  
The content of this tutorial itself is licensed under the terms and conditions of the [Creative Commons Attribution (CC BY 4.0) license](https://creativecommons.org/licenses/by/4.0/legalcode.en), and the underlying source code used to format and display that content is licensed under the [MIT license](https://github.com/NanoBiostructuresRG/NumpyTutorial/blob/main/LICENSE). See the LICENSE files for full details.

### Attribution
If you use or adapt this material, please provide appropriate credit to the original authors and repository:
[https://github.com/NanoBiostructuresRG](https://github.com/NanoBiostructuresRG)