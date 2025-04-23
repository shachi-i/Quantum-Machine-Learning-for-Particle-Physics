# Quantum Machine Learning for Particle Classification using CERN Open Data

## Objective

This project aims to show the application of **Quantum Machine Learning (QML)** for classifying high-energy physics particles using **CERN Open Data**. A classical machine learning model is used as a baseline, and its performance is compared against a **Variational Quantum Classifier (VQC)** implemented using **Qiskit**.

---

##  Dataset

- **Source**: [CERN Open Data Portal](https://opendata.cern.ch/)
- **Format**: `.root`
- **Library Used**: `uproot` to parse ROOT files
- **Sample Size**: ~7.9 million events

---

##  Models

###  Classical Model
- **Type**: Random Forest Classifier
- **Library**: Scikit-learn
- **Purpose**: Establish a performance baseline

###  Quantum Model
- **Type**: Variational Quantum Classifier (VQC)
- **Library**: Qiskit Machine Learning

---

##  Insights

- Quantum models benefit greatly from well-scaled, low-dimensional feature spaces.
- Classical models still outperform on large datasets but QML offers exciting research opportunities.

---



