# Colon-Cell-Image-Classification

## Problem Statement

Accurate classification of colon cell types in histopathology images plays a vital role in cancer diagnostics, providing detailed insights into tissue structure and pathological conditions. In this study, we focus on designing a machine learning system capable of address two related tasks:

- Task 1: Determine whether a given colon cell image represents a cancerous cell or not (isCancerous), framing it as a binary classification problem.
- Task 2: Classifying individual colon cells into one of four types: fibroblast, inflammatory, epithelial, or others.

Both tasks leverage RGB image patches of size 27x27 pixels, cropped from biopsy slides provided in a modified version of the CRCHistoPhenotypes dataset. Our goal is to build supervised classification models using Convolutional Neural Networks (CNNs). We utilizes macro F1-score to handle potential class imbalance in cancerous vs. non-cancerous labels and emphasize equal importance across all four classes and thus adopt macro-averaged f1_score as our performance metric, aiming to achieve at least 90% F1-score, inspired by benchmarks from the original dataset publication (Sirinukunwattana et al., 2016). Our approach involves comprehensive data preprocessing, class balancing techniques, and iterative tuning of model architectures and hyperparameters

Initial models will be iteratively improved using techniques such as data augmentation, dropout, and class weighting. The model’s performance will be compared against baselines and literature benchmarks to assess generalisability and robustness. Limitations include class imbalance and restricted image resolution, though findings aim to advance automated analysis pipelines in digital pathology, supporting both binary and multi-class cell classification tasks.
