# AI-Driven Defect Detection in Automotive Manufacturing

**Published in Nature Scientific Reports (2025)**  
*Quality 4.0 · Predictive Quality Management · Machine Learning*

---

## Overview

This project implements a machine learning pipeline for classifying engine valve defects in high-precision automotive manufacturing, framed within the Quality 4.0 PMQ (Predictive Maintenance & Quality) framework.

The work demonstrates that ML-based inspection can replace manual visual checks with significantly higher accuracy and speed — a finding published in *Nature Scientific Reports*.

---

## Results

| Metric | Value |
|---|---|
| F1 Score | 98% |
| AUC | 99% |
| Reduction in manual inspection time | 60% |
| Improvement in defect detection accuracy | 40%+ |
| Dataset size | 1,000 engine valves |

**Best models:** Gradient Boosting · Random Forest

---

## Methodology

1. **Data preparation** — feature engineering on valve measurement data, handling class imbalance
2. **Model training** — compared Gradient Boosting, Random Forest, SVM, and Logistic Regression
3. **Evaluation** — ROC-AUC, F1, confusion matrix, feature importance analysis
4. **Framework** — structured within the PMQ (Predictive Maintenance & Quality) Quality 4.0 framework

---

> **Note on data:** The original dataset is proprietary. A synthetic demonstration dataset is included.

---

## Publication

> Allam, M. et al. (2025). *AI-Driven Defect Prediction in Automotive Manufacturing*. Nature Scientific Reports.  
> [Link to paper — add DOI here]

---

## Tech stack

Python · Scikit-learn · Pandas · Matplotlib · Seaborn
