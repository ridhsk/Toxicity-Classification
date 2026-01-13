# Toxicity Prediction from SMILES using Machine Learning

This project focuses on predicting whether a chemical compound is toxic or non-toxic
based on its molecular structure represented as SMILES strings. The work applies
cheminformatics techniques and machine learning models to enable scalable and
cost-effective toxicity screening.

## Project Overview
- Chemical compounds are represented using SMILES notation
- Structural features are extracted using molecular fingerprints and vectorization techniques
- Multiple machine learning models are trained and evaluated
- The system predicts toxicity for both labeled and unlabeled compounds

## Feature Engineering
- Morgan Fingerprints (ECFP, radius=2, 2048 bits) using RDKit
- Character-level n-gram vectorization of SMILES strings (2–4 grams)

## Models Implemented
- Logistic Regression
- Random Forest
- XGBoost
- Support Vector Classifier (LinearSVC)

## Dataset
- Balanced dataset of 40,000 compounds
  - 20,000 toxic
  - 20,000 non-toxic
- Data sourced from publicly available chemical databases
- Binary classification: toxic vs non-toxic

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score

## Results Summary
- XGBoost achieved the highest overall performance
- Random Forest showed strong generalization
- Linear SVC performed well with Morgan fingerprints
- Logistic Regression served as a fast and interpretable baseline

## My Contribution
- Feature extraction using Morgan fingerprints with RDKit
- Model training and evaluation for toxicity classification
- Comparative analysis of machine learning models
- Prediction on unlabeled chemical compounds

## Tech Stack
- Python
- RDKit
- scikit-learn
- XGBoost
- NumPy, Pandas

## Reference
Detailed methodology, experiments, and results are documented in the project report
included in this repository.
