# decoding-the-city
Data Science and AI approaches to analyze and explain urban accessibility patterns in Porto.

# Decoding the City: Data Science and AI for Understanding Urban Accessibility

## Overview

**Decoding the City** is a research-oriented project that applies **Data Science** and **Artificial Intelligence (AI)** to analyze and explain **urban accessibility** in **Porto, Portugal**.  
Using **geospatial analysis**, **clustering**, and **Explainable AI (XAI)**, it studies how different population groups — particularly the elderly — access essential services such as healthcare, education, commerce, and transportation.

The project aims to generate insights that support **inclusive urban planning**, **mobility equity**, and **data-driven decision-making** for more sustainable cities.

---

## Motivation

Accessibility is a core component of urban equity and social inclusion.  
By combining open data and AI, this project seeks to:

- Identify **patterns of inequality in accessibility** across Porto’s parishes.  
- Apply **machine learning and clustering** to classify areas by service proximity.  
- Use **explainable AI** to understand *why* certain areas show better or worse accessibility.  

---

## Project Structure

**Repository layout**

- **README.md** — Project documentation and overview  
- **requirements.txt** — Python dependencies  
- **.gitignore** — Files and folders excluded from version control  

**Main folders**
- **data/** — Datasets *(not included in the repository)*  
- **notebooks/** — Jupyter notebooks for data analysis and modeling  
  - `Initial_setup.ipynb`
  - `case_study_prep.ipynb`
  - `data_exploration_base.ipynb`
  - `data_exploration.ipynb`
  - `clustering_base.ipynb`
  - `clustering.ipynb`
  - `explainable_ai_clustering_base.ipynb`
  - `explainable_ai_clustering.ipynb`
-  **src/** — Optional Python scripts and helper functions  
-  **docs/** — Generated charts, figures, and documentation



---

### **Notebooks (`/notebooks/`)**

| Notebook | Description |
|-----------|-------------|
| **Initial_setup.ipynb** | Loads datasets and sets up the environment. |
| **data_exploration.ipynb** | Exploratory and geospatial data analysis. |
| **clustering.ipynb** | Clustering experiments using K-Means, DBSCAN, etc. |
| **explainable_ai_clustering.ipynb** | Explainability analysis with SHAP. |
| **case_study_prep.ipynb** | Prepares final outputs and maps for reporting. |

---

### **Supporting Files**

| File | Description |
|------|--------------|
| **requirements.txt** | Python dependencies for environment setup. |
| **.gitignore** | Excludes unnecessary or large files (like `/data/`). |
| **src/** | Optional folder for helper scripts. |
| **docs/** | For generated figures and documentation. |

---

## Objectives

- Measure and visualize **urban accessibility** in Porto.  
- Detect **spatial patterns** using clustering.  
- Apply **Explainable AI (XAI)** to interpret models.  
- Promote **inclusive, data-driven urban planning**.

---

## Setup Instructions

### Create and activate a virtual environment
```bash
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -U pip

pip install -r requirements.txt

jupyter lab
# or
jupyter notebook



