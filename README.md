# decoding-the-city
Data Science and AI approaches to analyze and explain urban accessibility patterns in Porto.

# Decoding the City: Data Science and AI for Understanding Urban Accessibility

## Overview

**Decoding the City** is a research-oriented project that applies **Data Science** and **Artificial Intelligence (AI)** to analyze and explain **urban accessibility** in the city of **Porto, Portugal**.  
Through **geospatial analysis**, **clustering**, and **Explainable AI (XAI)**, the project studies how different population groups — particularly the elderly — access essential services such as healthcare, education, commerce, and transportation.

The goal is to generate insights that support **inclusive urban planning**, **mobility equity**, and **data-driven decision-making** for more sustainable and human-centered cities.

---

## Motivation

Accessibility is one of the core aspects of urban equity and social inclusion.  
By integrating open data and AI, this project aims to:

- Identify **patterns of inequality in urban accessibility** across Porto’s parishes.  
- Apply **machine learning and clustering** to classify areas based on service proximity.  
- Use **explainable AI methods** to understand *why* certain areas show better or worse accessibility.  

---

## Project Structure

---

## 📁 File Descriptions

### **Data Files (`/data/`)**

| File | Description |
|------|--------------|
| **average_distance_to_services.csv** | Contains the average distance from each parish to various categories of essential services (e.g., hospitals, schools, markets). This serves as the main accessibility metric. |
| **population_65_plus.csv** | Demographic data showing the proportion of residents aged 65 and older per parish, used to analyze accessibility for vulnerable populations. |
| **porto_parishes.csv** | Geospatial data defining the administrative boundaries of Porto’s parishes. Enables mapping and spatial visualization of results. |
| **services_by_category.csv** | List of categorized services (e.g., Health, Education, Commerce) with geographic coordinates, used to compute service density and proximity. |

---

### **Notebooks (`/notebooks/`)**

| Notebook | Description |
|-----------|-------------|
| **Initial_setup.ipynb** | Initializes the project, loads datasets, and ensures the environment is ready for analysis. |
| **data_exploration_base.ipynb** | Basic exploratory analysis: statistical summaries, missing values, and simple visualizations. |
| **data_exploration.ipynb** | Advanced geospatial data exploration using maps and accessibility metrics. |
| **clustering_base.ipynb** | First clustering tests using methods such as K-Means and DBSCAN to identify groups of similar parishes. |
| **clustering.ipynb** | Optimized clustering with fine-tuned parameters and validation metrics. |
| **explainable_ai_clustering_base.ipynb** | Introduces explainability tools to interpret which features influence clustering results. |
| **explainable_ai_clustering.ipynb** | Advanced explainability analysis with SHAP and visualization of feature importance. |
| **case_study_prep.ipynb** | Prepares outputs, maps, and summaries for the final case study and reporting. |

---

### **Supporting Files**

| File | Description |
|------|--------------|
| **requirements.txt** | Lists Python dependencies needed to reproduce the environment. |
| **.gitignore** | Defines which files and folders are ignored by Git (temporary data, virtual environments, caches, etc.). |
| **src/** | Optional folder for helper scripts or reusable Python modules. |
| **docs/** | Folder for generated reports, charts, and exported figures. |

---

## Objectives

- Measure **urban accessibility** and service proximity across Porto.  
- Detect **spatial patterns** using clustering algorithms.  
- Apply **Explainable AI** to interpret model behavior and key drivers.  
- Support **inclusive and evidence-based urban planning**.

---

## ⚙️ Setup Instructions

### 1️⃣ Create and activate a virtual environment
```bash
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -U pip

pip install -r requirements.txt

jupyter lab
# or
jupyter notebook


