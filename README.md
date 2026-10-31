# Lab 5: Linear Model Selection & Regularization

This repository contains the complete implementation, analysis, and report for **Lab 5: Linear Model Selection & Regularization** (IT171IU - Statistical Learning).

## Table of Contents
- [Overview](#overview)
- [Dataset Summary](#dataset-summary)
- [Repository Structure](#repository-structure)
- [Installation & Setup](#installation--setup)
- [Running the Code](#running-the-code)
- [Exercise Summaries](#exercise-summaries)
- [Figure Insertion Guide](#figure-insertion-guide)

---

## Overview
This lab explores methods for selecting, regularizing, and reducing linear models to enhance prediction accuracy and interpretability:
1. **Subset Selection:** Forward Stepwise Selection, Best-Subset Selection ($C_p$, validation set, cross-validation).
2. **Regularization:** Ridge Regression ($L_2$ penalty) and Lasso ($L_1$ penalty) coefficient paths and $\lambda$ tuning.
3. **Dimension Reduction:** Principal Components Regression (PCR) and Partial Least Squares (PLS).
4. **Resampling Techniques:** Nested Cross-Validation to evaluate model generalization without data leakage.

---

## Dataset Summary
- **Hitters:** Major League Baseball statistics used for predicting player salaries.
- **College:** US News and World Report college data used to predict the number of applications received (`Apps`).
- **Boston:** Housing and demographic data used to predict per-capita crime rate (`crim`).
- **Diabetes:** Clinical baseline metrics used to predict disease progression one year after baseline.
- **Simulated Datasets:** Synthetic datasets designed to evaluate model selection accuracy against known ground truths.
 
 ---

## Repository Structure
```text
IT171IU_Lab05_TranHongPhuc_ITDSIU24039/
├── IT171IU_Lab05_TranHongPhuc_ITDSIU24039.ipynb   
├── IT171IU_Lab05_Report.pdf                     
└── README.md                                    

