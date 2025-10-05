# Spatial Transcriptomics of Breast Cancer and Lymph Node Metastases

This repository presents an **interpretable spatial transcriptomics analysis** of primary breast tumors and matched lymph node metastases (LNMT). The project integrates **10x Visium spatial gene expression** with **scRNA-seq–derived gene programs** to characterize tissue architecture, regional signaling, and spatial remodeling associated with metastatic progression.

---

## Overview

- **Program scoring** using curated signatures for epithelial, immune, stromal, and proliferation modules  
- **Region annotation** via top-quantile masking and label assignment  
- **Compact spatial visualizations** of regional activity and composition  
- **Region–region adjacency** analysis quantifying tissue-level organization  
- **Differential expression** profiling between primary tumors and LNMT  

---

## Interpretation

The analysis emphasizes **interpretability and reproducibility**, using region-based annotation to capture functional tissue compartments **without reliance on unsupervised clustering**. This approach allows transparent, biologically meaningful mapping of tumor and microenvironmental zones.

---

## Notebook Philosophy

The notebook is written as a **transparent, narrative-style analysis**, where code, results, and interpretation are fully integrated. Each cell is **highly commented**, explaining not only what each step does but also the **reasoning and biological rationale** behind it. Figures and annotations are embedded throughout, making the workflow self-explanatory and reproducible from start to finish.

---

## Quick Start

📘 View the full notebook:  
[spatial_mapping.ipynb on nbviewer](https://nbviewer.org/github/Sally332/Spatial_Mapping/blob/main/spatial_mapping.ipynb)

---

## Notes

All steps are designed for **clarity, reproducibility, and communication** of spatial organization in cancer tissues. The repository illustrates how simple, interpretable spatial workflows can complement more complex graph-based models such as *SpatialMMKPNN*.

---

## License
MIT License

## Author
**Sally Yepes**  
📧 sallyepes233@gmail.com

