# Spatial Transcriptomics of Breast Cancer and Lymph Node Metastases

**A reproducible and interpretable analysis of tumor architecture using 10x Visium spatial transcriptomics**

---

## Overview
This repository presents an interpretable spatial transcriptomics analysis of **primary breast tumors** and **matched lymph node metastases (LNMT)**, designed to uncover how tumor, immune, and stromal programs reorganize across disease progression. By integrating 10x Visium spatial gene expression with **scRNA-seq–derived functional signatures**, the analysis identifies **immune exclusion zones, stromal barriers, and proliferative niches** within the tumor microenvironment. It serves as both a **biological case study** of metastatic architecture and a **methodological framework** for transparent, rule-based spatial mapping that connects single-cell information to tissue-level organization.

## Highlights
- **Spatial Logic of Metastasis:** Quantifies how immune, stromal, and proliferative zones reorganize between primary tumors and lymph node metastases  
- **Transparent Spatial Annotation:** Uses biologically grounded, rule-based region labeling instead of clustering or latent embeddings  
- **Multi-Scale Integration:** Connects single-cell–derived gene programs to tissue-level spatial structure, linking molecular activity with morphology  

---

## Notebook Design
The notebook follows a **narrative, fully commented structure** where code, figures, and interpretation are interleaved. Each section explains both the computational rationale and biological reasoning. All figures and outputs are embedded inline for an end-to-end, self-contained analysis.

📄 A **static PDF version** of the notebook, including all code and figures, is available in  
[`docs/spatial_mapping_full.pdf`](https://github.com/Sally332/Spatial_Mapping/blob/main/docs/spatial_mapping_full.pdf).

---

## Quick Start
📘 **Interactive notebook:**  
[`spatial_mapping.ipynb`](https://github.com/Sally332/Spatial_Mapping/blob/main/spatial_mapping.ipynb)

📄 **Detailed documentation:**  
See the long README in this repository for a full description of datasets, methods, and results.

---

## Citation
If you use or adapt this framework, please cite:

> Yepes S. *Spatial Transcriptomics of Breast Cancer and Lymph Node Metastases.* GitHub, 2025.  
> Available at: [https://github.com/Sally332/Spatial_Mapping](https://github.com/Sally332/Spatial_Mapping)

---
