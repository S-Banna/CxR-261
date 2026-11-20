# ACDC Cardiac MRI Classification

CMPS 261 Machine Learning Project – Team 7

We classify cardiac MRI patients into five diagnostic groups using three pipelines:

1. Expert masks + Logistic Regression
2. Random Forest segmentation + Logistic Regression
3. U-Net segmentation + Logistic Regression

## Results

| Pipeline | Test Accuracy |
|---|---|
| Expert masks | 90% |
| Random Forest | 28% |
| U-Net | 86% |

The U-Net achieved a segmentation Dice score of **0.927**.

## Files

- `project.ipynb` – Code, training, experiments, and evaluation.
- `models/` – Saved trained models.

**Dataset:** [ACDC](https://www.creatis.insa-lyon.fr/Challenge/acdc/)
