# Colon-Cell-Image-Classification

## Overview

This project focuses on classifying colon cell types in histopathology images, an important step in cancer diagnostics. The goal is to build Convolutional Neural Network (CNN) models to solve two tasks:

1. Binary Classification – Determine whether a colon cell is cancerous or non-cancerous.

2. Multi-Class Classification – Categorize individual cells into one of four types:
   - Fibroblast
   - Inflammatory
   - Epithelial
   - Others

The dataset is derived from a modified version of the CRCHistoPhenotypes dataset, consisting of 27×27 RGB patches extracted from biopsy slides.

## Key Details

Performance Metric: Macro F1-Score

Techniques Used:

- Data preprocessing & balancing
- Data augmentation
- Dropout regularization
- Class weighting
- Iterative hyperparameter tuning

## Results

Binary classification model:

- Accuracy : 0.93
- Macro F1 Score : 0.92
- ROC-AUC Score : 0.98

Multi-class classification model:

- Accuracy: 0.695
- Macro F1 Score : 0.629
