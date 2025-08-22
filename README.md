# Housing Affordability for Key Workers in London (2010–2025)

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Tableau](https://img.shields.io/badge/Tableau-Public-blue.svg)](https://public.tableau.com/app/profile/raul.c1685/vizzes)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://github.com/raulcimpe/housing-affordability-london/blob/main/notebooks/london_housing_final.ipynb)

This repository contains a final-year project developed at **London South Bank University (LSBU)**.  
It investigates to what extent **key public sector workers in London** — teachers, NHS nurses, and TfL bus drivers — are excluded from **affordable home ownership** between **2010 and 2025**.

> **Data policy (BYOD):** This repository does not include raw datasets or the final written report.  
> Instead, it provides the project structure, Jupyter/Colab notebooks, Tableau dashboards, and documentation.  
> To replicate results, use public UK datasets (ONS, NHS, DfE, TfL) with the provided notebooks.

---

## 🔍 Introduction
Affordability pressures in global cities can displace essential workers and strain public services.  
This project applies recognised **housing affordability metrics** — primarily the **House Price to Income Ratio (HPIR)** — across **32 London boroughs** and key worker groups to quantify the affordability gap.

The project follows the **CRISP-DM methodology**, ensuring a structured approach:
- **Business Understanding:** Define research problem and scope.  
- **Data Understanding & Preparation:** Collect, clean, and transform datasets.  
- **Modelling & Evaluation:** Apply affordability metrics and test thresholds.  
- **Deployment:** Communicate results via Tableau dashboards.  

---
## 🛠️ Technologies
- **Python** (pandas, matplotlib, seaborn) – Data analysis and preparation  
- **Jupyter/Colab** – Reproducible notebooks for analysis  
- **Tableau Public** – Interactive dashboards and visualisation  
- **CRISP-DM** – Methodological framework for structuring the project  

## ⚙️ Project Structure
```
housing-affordability-london/
├── notebooks/ # Jupyter/Colab notebooks (analysis & data prep)
│ ├── london_housing_final.ipynb
│ └── README.md
├── dashboards/ # Tableau workbooks and exports
│ └── README.md
├── LICENSE # MIT License
└── README.md # Main project documentation
```
---


👉 Explore [Notebooks](notebooks/README.md) and [Dashboards](dashboards/README.md) for details.

---

## 📊 Dashboards
Interactive Tableau dashboards are available on **[Tableau Public](https://public.tableau.com/app/profile/raul.c1685/vizzes)**.

Dashboards include:
Dashboards include:
- **House Price Index (HPI) Trends (2010–2025):** Comparison of London boroughs vs UK average.  
- **Key Worker Salary Trends and Affordability:** Evolution of NHS, teachers, and TfL bus driver salaries against housing costs.  
- **Affordability Threshold Breach Years:** Identification of when HPIR exceeded the critical 8.5 threshold.  
- **Borough Comparisons:** Analysis of the most and least affordable boroughs in selected years (2010, 2015, 2020, 2025).  
- **Deposit as % of Salary (2025):** Required upfront costs relative to annual income.  
---

## 📒 Notebooks
The analysis is fully reproducible using the provided Jupyter/Colab notebook:

- `london_housing_final.ipynb` — End-to-end workflow covering:
  - Data exploration and cleaning  
  - Calculation of affordability ratios (HPIR)  
  - Borough-level comparisons  
  - Preparation of datasets for Tableau visualisations  

---

## ⚙️ Quickstart
To run the notebooks locally:

```bash
# 1. Clone this repository
git clone https://github.com/raulcimpe/housing-affordability-london.git
cd housing-affordability-london

# 2. Create a virtual environment
python -m venv .venv

# 3. Activate it
# On Windows
.venv\Scripts\activate
# On Linux / Mac
source .venv/bin/activate

# 4. Install dependencies (if requirements.txt is provided)
pip install -r requirements.txt
```
## 📜 License
This project is licensed under the MIT License – see the LICENSE file for details.








