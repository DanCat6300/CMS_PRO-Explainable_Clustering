# Explainable Clustering for Big Geodata Search
**Project:** CMS-PRO Research Project  
**Author:** Long Tran (5192922)  
**Supervisors:** Prof. Dr. Lars Bernard, Dr. rer. nat. Auriol Degbelo  
**Institution:** Technische Universität Dresden

---

## Abstract
As global geodata repositories grow gradually in volume, traditional search functions on flat lists become increasingly overwhelming. This project prototypes a pipeline for **multimodal data clustering** and **automated human-readable explanations** for the [OneStop4All](https://onestop4all.nfdi4earth.de/) portal. 

We address two primary research questions:
1. Identifying the optimal configuration for multimodal clustering (Spatial, Temporal, and Topical).
2. Generating and evaluating faithful cluster explanations using Large Language Models.

---

## Setup Note
- Please replace any directory path in the notebooks to your preference
- In the Explainer notebook, an API token is required to access OpenAI models
- I recommend running this repository with Google Colab to avoid missing package issues.
- Please do not hesitate to contact me for support

## Data & Storage
For convenience, below is the access to Google Drive folder storing the project

* **Project Data Folder:** [Drive](https://drive.google.com/drive/folders/1dE6AH3sEhinqSGXgCEiteeFH7GmIXHwO?usp=drive_link)  
The Drive folder includes notebooks, datasets, embeddings, results, and archives 
---

## Repository Structure
```text
├── notebooks/
│   ├── TUD_Research_Project_Param_Sweep.ipynb  # HDBSCAN parameter optimization
│   ├── TUD_Research_Project_Preparation.ipynb  # Cleaning and encoding logic
│   ├── TUD_Research_Project_Retrieval.ipynb    # Automated retrieval from external sources
│   └── TUD-Research_Project-Explainer.ipynb    # c-TF-IDF and GPT-5.4 explanation pipeline
├── results/
│   ├── cluster_results/                 # Collection of clustering results
│   └── explanation_results/          # Collection of explanation generation results
└── README.md
```
