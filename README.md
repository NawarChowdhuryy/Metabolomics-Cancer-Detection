# Colorectal Cancer Classification using GC-MS Metabolomics and Explainable AI (SHAP)

## Overview
This repository contains the machine learning code, data preprocessing pipeline, and customized dataset used in our thesis research on Colorectal Cancer (CRC) detection. The project focuses on leveraging Gas Chromatography–Mass Spectrometry (GC-MS) volatile organic compound (VOC) profiles combined with explainable artificial intelligence (XAI) techniques to build accurate and interpretable diagnostic models.

## Dataset Description
- **Source:** Adapted and customized from the foundational study by Durán Acevedo et al. (2025) (*Cancers*, 17(17), 2742).
- **Features:** The original dataset evaluated both GC-MS and electronic nose systems across 136 samples from 68 participants. For this framework, the working dataset was specifically curated, preprocessed, and restricted to **68 GC-MS-derived VOC features**.

## Project Workflow & Methodology
1. **Data Preprocessing & Feature Selection:** Cleaned and formatted raw GC-MS volatile compound signatures for model compatibility.
2. **Model Training & Evaluation:** Trained state-of-the-art classification algorithms, including LightGBM, Naive Bayes, and Scikit-learn classifiers, to predict cancer status.
3. **Model Interpretability (XAI):** Implemented **SHAP (SHapley Additive exPlanations)** to analyze feature importance, identify biomarker signatures, and explain model outputs transparently.

## Repository Structure
- `dataset/` — Customized and preprocessed CSV dataset files.
- `notebooks/` — Jupyter Notebooks containing exploratory data analysis, model training, and evaluation workflows.
- `src/` — Python helper functions and scripts for data processing and SHAP visualizations.
- `README.md` — Project documentation and setup guide.

## How to Use
1. Clone the repository: `git clone https://github.com/your-username/your-repo-name.git`
2. Install required packages: `pip install -r requirements.txt`
3. Open and run the Jupyter notebooks in `notebooks/` to reproduce model training and SHAP visualizations.

## Citation
If you use this repository or dataset, please cite the foundational publication:
> Durán Acevedo, et al. (2025). *Cancers*, 17(17), 2742. DOI: [10.3390/cancers17172742](https://doi.org/10.3390/cancers17172742)
