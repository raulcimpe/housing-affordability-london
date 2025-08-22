# Analysis of housing affordability for key workers in London (2010–2025) using Python (CRISP-DM) and Tableau dashboards.

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  
[![Tableau: Public Dashboards](https://img.shields.io/badge/Tableau-Public-blue)](https://public.tableau.com/app/profile/raul.c1685/vizzes)

This repository contains a final-year project developed at **London South Bank University (LSBU)**.  
It investigates to what extent **key public sector workers in London** — teachers, NHS nurses, and TfL bus drivers —  
are excluded from **affordable home ownership** between **2010 and 2025**.

> **Data policy (BYOD):** This repository does **not** include raw datasets or the final written report.  
> Instead, it provides the project structure, Jupyter/Colab notebooks, Tableau dashboards, and documentation.  
> To replicate results, use public UK datasets (ONS, NHS, DfE, TfL) with the provided notebooks.

---

## 🔍 Introduction
Affordability pressures in global cities can displace essential workers and strain public services.  
This project applies recognised housing affordability metrics — primarily the **House Price to Income Ratio (HPIR)** —  
across **32 London boroughs** and key worker groups to quantify the affordability gap.  

The project follows the **CRISP-DM methodology**, ensuring a structured approach:  
- **Business Understanding**: Define the research problem and scope.  
- **Data Understanding & Preparation**: Explore, clean, and transform datasets.  
- **Modeling & Evaluation**: Apply affordability metrics and test thresholds.  
- **Deployment**: Communicate results via Tableau dashboards.  

---

## ⚙️ Project Structure
```
housing-affordability-london/
├── notebooks/ # Jupyter/Colab notebooks (analysis & data prep)
│ └── london_housing_final.ipynb
├── dashboards/ # Tableau workbooks and exports
│ └── [links to Tableau Public dashboards]
├── LICENSE # MIT License
└── README.md # Project documentation
```
---

## 📊 Dashboards
Interactive Tableau dashboards are available on **Tableau Public**:  
👉 [View Dashboards](https://public.tableau.com/app/profile/raul.c1685/vizzes)  

Dashboards include:  
- **House Price Index (HPI) Trends**: London vs UK average (2010–2025)  
- **Key Worker Salary Trends**: NHS staff, teachers, and TfL bus drivers  
- **Affordability Metrics**: HPIR, threshold breaches, and deposit ratios  
- **Borough Comparisons**: Most vs least affordable areas  

---

## 📓 Notebooks
The analysis is fully reproducible using the provided Jupyter/Colab notebook:  
- **`london_housing_final.ipynb`** — End-to-end workflow covering:  
  - Data exploration and cleaning  
  - Calculation of affordability ratios (HPIR)  
  - Borough-level comparisons  
  - Preparation of datasets for Tableau visualisations  

---

## 🚀 Quickstart
If you wish to run the notebooks locally:  

```bash
# 1. Clone this repository
git clone https://github.com/raulcimpe/housing-affordability-london.git
cd housing-affordability-london

# 2. Create a virtual environment
python -m venv .venv

# 3. Activate it
# On Windows
.venv\Scripts\activate
# On Linux/Mac
source .venv/bin/activate

# 4. Install dependencies (if requirements.txt is provided)
pip install -r requirements.txt
```
## 📜 License
This project is licensed under the MIT License – see the LICENSE file for details.



