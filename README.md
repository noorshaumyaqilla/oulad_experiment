# OULAD LIME Experiment

This repository contains the Jupyter notebook and supporting files used for the OULAD LIME experiment. It includes the main analysis notebook, the datasets used for modeling, the trained model artifacts, and the generated figures.

## Files included

- ch4v2.ipynb: the main Jupyter notebook for the experiment
- assessments.csv, courses.csv, studentAssessment.csv, studentInfo.csv, studentRegistration.csv, vle.csv: datasets used in the analysis
- model_backend/: trained model files and preprocessing artifacts
- Figure_*.png: visual outputs generated from the notebook

## How to run

1. Open the repository folder in a Python environment.
2. Install the required packages:
```bash
pip install jupyter pandas numpy scikit-learn xgboost lime matplotlib seaborn
```

3. Start Jupyter Notebook:
```bash
jupyter notebook
```

4. Open ch4v2.ipynb and run the cells in order.

## Notes

- The notebook is the main entry point for the experiment.
- The repository excludes the larger studentVle.csv file because of GitHub size limits.
- If you want to reproduce the full workflow exactly, place the missing file in the repository root before running the notebook.
