<<<<<<< HEAD
=======
cat > README.md <<'EOF'
>>>>>>> e07aeee (Initial commit: BYOD structure, readmes, .gitignore, MIT license)
# Housing Affordability for Key Workers in London (2010–2025)

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![View Dashboards](https://img.shields.io/badge/Tableau-Public-blue)](https://public.tableau.com/app/profile/raul.c1685/vizzes)

This repository contains a final-year project developed at **London South Bank University (LSBU)**.  
It investigates to what extent **key public sector workers in London** — teachers, NHS nurses, and TfL bus drivers — are excluded from **affordable home ownership** between **2010 and 2025**.

> **Data policy (BYOD):** This repository does **not** include datasets or the final written report.  
> Bring Your Own Data: instructions below show how to run the notebook with your own local copies of the public sources.

<<<<<<< HEAD
---

=======
>>>>>>> e07aeee (Initial commit: BYOD structure, readmes, .gitignore, MIT license)
## 🔎 Introduction
Affordability pressures in global cities can displace essential workers and strain public services.  
This project applies recognised metrics — primarily the **House Price to Income Ratio (HPIR)** and related affordability ratios — across **32 London boroughs** and key worker groups to quantify the affordability gap.

The analysis is implemented in **Python (Google Colab / local)** and visualised with **Tableau Public**.

<<<<<<< HEAD
---

=======
>>>>>>> e07aeee (Initial commit: BYOD structure, readmes, .gitignore, MIT license)
## 🧭 Method (CRISP-DM)
1. **Business Understanding** – Define the affordability question for key workers.  
2. **Data Understanding** – Explore official sources (ONS, DfE, NHS Pay, TfL).  
3. **Data Preparation** – Clean, align, and reshape to analysis-ready formats (performed locally).  
4. **Modeling / Calculation** – HPIR, affordability ratios/thresholds, borough comparisons.  
5. **Evaluation** – Temporal and spatial interpretation; sensitivity checks.  
6. **Deployment** – Interactive dashboards on Tableau Public; notebook for reproducibility (BYOD).

<<<<<<< HEAD
---

=======
>>>>>>> e07aeee (Initial commit: BYOD structure, readmes, .gitignore, MIT license)
## 📈 Dashboards (Tableau Public)
Browse the interactive visuals:  
**https://public.tableau.com/app/profile/raul.c1685/vizzes**

<<<<<<< HEAD
---

=======
>>>>>>> e07aeee (Initial commit: BYOD structure, readmes, .gitignore, MIT license)
## 💻 Reproducibility (BYOD: no datasets in repo)
This project ships **no data**. To run locally or in Colab:

1. **Download public datasets** from the original sources (e.g., ONS House Price Index, DfE teachers’ pay, NHS Agenda for Change, TfL pay).  
2. Place files in a local directory of your choice (kept **outside** the repository).  
3. Open `notebooks/london_housing_final.ipynb` and set a data directory variable:

```python
import os

<<<<<<< HEAD
# Detect Colab vs local
=======
>>>>>>> e07aeee (Initial commit: BYOD structure, readmes, .gitignore, MIT license)
IN_COLAB = "google.colab" in str(getattr(__import__("sys"), "modules", {}))
if IN_COLAB:
    from google.colab import drive
    drive.mount("/content/drive")
    DATA_DIR = "/content/drive/MyDrive/Final Project 2025"
else:
<<<<<<< HEAD
    # Set via environment variable or edit this path
    DATA_DIR = os.environ.get("DATA_DIR", r"C:\path\to\your\datasets")

# Example usage:
price_index_path = os.path.join(DATA_DIR, "price_index.xlsx")
teachers_path    = os.path.join(DATA_DIR, "teachers_pay.csv")
# ... add remaining files you use locally
=======
    DATA_DIR = os.environ.get("DATA_DIR", r"C:\path\to\your\datasets")

price_index_path = os.path.join(DATA_DIR, "price_index.xlsx")
teachers_path    = os.path.join(DATA_DIR, "teachers_pay.csv")
# ... add remaining files you use locally
Keep your datasets out of Git to respect licenses/ToS and avoid large files.

🗂️ Repository Structure
arduino
Copy
Edit
housing-affordability-london/
├── notebooks/
│   └── london_housing_final.ipynb     # add later
├── dashboards/
│   └── README.md
├── .gitignore
├── LICENSE
└── README.md
⚙️ Environment
Python 3.10+

Common stack: pandas, numpy, matplotlib, seaborn, (optionally) jupyter/colab

Example setup:

bash
Copy
Edit
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS / Linux
source .venv/bin/activate

pip install -r requirements.txt
>>>>>>> e07aeee (Initial commit: BYOD structure, readmes, .gitignore, MIT license)
