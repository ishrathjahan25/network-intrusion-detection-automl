# Network Intrusion Detection using AutoML

Final year project (CSEC3100D), De Montfort University Dubai.

## Overview
An intrusion detection system built with H2O AutoML on the CICIDS2017 dataset, compared with Logistic Regression, Random Forest and TPOT, and explained with SHAP. A Streamlit app lets you explore the results.

## Results
- AutoML model: F1 = 0.9999, 3 misclassifications on 57,220 held-out flows
- Label-poisoning test: 8-point drop in DoS detection at 30% poisoning
- Cost model comparing missed detections with false-alert workload

## Tools
Python, pandas, scikit-learn, XGBoost, H2O AutoML, SHAP, Streamlit

## Repository contents
- app.py: Streamlit application
- network_intrusion_detection_automl.ipynb: full analysis notebook
- images/: confusion matrices and SHAP plots
- report/: final project report (PDF)

## Run it
pip install -r requirements.txt
streamlit run app.py

## Dataset
CICIDS2017, Canadian Institute for Cybersecurity (download from the official page). It is not included here because of its size.
