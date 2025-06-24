# Superconductor Critical Temperature Prediction

## Table of Contents- [Project Overview](#project-overview)- [Motivation](#motivation)- [Data Source](#data-source)- [Objectives](#objectives)- [Methods](#methods)- [Results](#results)- [Repository Structure](#repository-structure)- [References](#references)
---
## Project Overview
This project leverages machine learning models to predict the **critical temperature (TC)** of superconductors and to classify materials as **high-TC or low-TC**. The models used include **Ridge Regression**, **Lasso Regression**, **XGBoost**, and **Support Vector Machines (SVMs)**.
The analysis aims to guide the use of high-TC superconductors in **MRI machines**, reducing dependency on liquid helium by instead utilizing **liquid nitrogen**, which is more cost-effective and sustainable.

---
## Motivation
Superconductors, materials that conduct electricity with **zero resistance**, exhibit unique magnetic properties such as the **Meissner Effect**. They are essential in applications like **MRI machines, power grids, and quantum computing**.
Due to the high cost and scarcity of **liquid helium**, there's strong motivation to identify superconductors that operate above **77 K**, the boiling point of **liquid nitrogen**. These **high-TC superconductors** would allow MRI systems to run more economically.

---
## Data Source
The dataset used in this project was sourced from:
> K. Hamidieh, “A Data-Driven Statistical Model for Predicting the Critical Temperature of a Superconductor” (UCI Machine Learning Repository).
- 21,263 superconductor samples
- 81 elemental features

---
## Objectives
1. **Predict** the critical temperature (TC) using regression models:
   - Ridge Regression
   - Lasso Regression
   - XGBoost
2. **Classify** superconductors as high-TC (≥77K) or low-TC (<77K) using:
   - Support Vector Machines (SVM)

---
## Methods
- **Preprocessing**:
  - Scikit-learn used for feature scaling and model training
  - Dataset split into training/testing sets
- **Modeling**:
  - Regression: Ridge, Lasso, and XGBoost
  - Classification: SVM with RBF kernel
- **Evaluation Metrics**:
  - Root Mean Square Error (RMSE)
  - R² (coefficient of determination)
  - Precision (for classification)

---
## Results
### Regression Performance
| Model    | RMSE   | R²    |
|----------|--------|-------|
| Ridge    | 17.61  | 0.73  |
| Lasso    | 18.46  | 0.71  |
| XGBoost  | 10.02  | 0.91  |
- **XGBoost** had the lowest error and highest predictive power.

### Classification (SVM)
- **Precision Score**: 0.69
- Correctly identifies high-TC superconductors ~69% of the time.

---
## Repository Structure
```
Superconductor_Analysis/
├── data/
│   ├── xgboost_predicted_vs_actual.xls
│   └── lasso_ridge_predicted_vs_actual.xls
├── report/
│   ├── Final_Report.pdf
│   └── Presentation.pptx
├── scripts/
│   └── final_project.ipynb
├── images/
└── README.md
```

---
## References
1. Solymar et al. _Electrical Properties of Materials_, Oxford University Press, 2014.
2. DOE - https://www.energy.gov/science/doe-explainssuperconductivity
3. UC Berkeley Research - https://vcresearch.berkeley.edu/heising-simons/jame-analytis/drawn-superconducting-magnets
4. Hamidieh (2018), UCI Repository - https://doi.org/10.24432/C53P47
5. Europhysics News - https://doi.org/10.1051/epn/2012404
6. Premier Imaging - https://premierimaging.org/how-to-prepare-for-an-mri/
7. BBC Helium Shortage - https://www.bbc.com/future/article/20250331-why-helium-shortages-are-worrying-the-world
8. USGS - https://www.usgs.gov/centers/national-minerals-information-center/helium-statistics-and-information
9. NVIDIA - https://www.nvidia.com/en-us/glossary/xgboost/
10. MATLAB on SVM - https://www.mathworks.com/help/stats/support-vector-machines-for-binary-classification.html
11. C3 AI - https://c3.ai/glossary/data-science/root-mean-square-error-rmse/
