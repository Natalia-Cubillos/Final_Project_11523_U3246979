# Final Project — U3246979 (Natalia Cubillos)

## Overview
This repository contains two Jupyter notebooks developed for the final project submission.  
Each notebook demonstrates data analysis and model development in Python, from preprocessing to evaluation.

## Repository Structure
Final_Project_11523_U3246979/
├── oncloud_FinalProject_U3246979.ipynb # Analysis & modelling with cloud dataset
├── onpremises_FinalProject_U3246979.ipynb # Analysis & modelling with on-premises dataset
├── requirements.txt # Python dependencies
└── .gitignore # Excludes data & large files

## Requirements
- Python 3.9+
- Jupyter Notebook
- Python libraries:
  - numpy
  - pandas
  - matplotlib
  - seaborn
  - scikit-learn
  - imbalanced-learn

Install everything with:
```bash
pip install -r requirements.txt
git clone https://github.com/Natalia-Cubillos/Final_Project_11523_U3246979.git
cd Final_Project_11523_U3246979

python -m venv .venv
source .venv/bin/activate      # macOS/Linux
# .venv\Scripts\activate       # Windows

pip install -r requirements.txt
jupyter notebook
Open and run either notebook:

oncloud_FinalProject_U3246979.ipynb

onpremises_FinalProject_U3246979.ipynbExpected Output

When executed, the notebooks:

Load and process the respective datasets (not included in the repo).

Train classification models with scikit-learn.

Report metrics (accuracy, precision, recall, F1-score).

Plot diagnostics (e.g., confusion matrices, learning curves).

Conclude with insights comparing results.

Datasets

Data files are not included due to size constraints.
Place your local datasets alongside the notebooks to reproduce the full results.
