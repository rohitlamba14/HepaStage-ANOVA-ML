# HepaStage-ANOVA-ML

A Multi-Class Machine Learning Framework for Hepatitis C Stage Classification Using ANOVA-Based Feature Selection.

## Overview

This repository contains the implementation of a machine learning framework for classifying Hepatitis C into five diagnostic categories:

- Blood Donor
- Suspect Blood Donor
- Hepatitis C
- Fibrosis
- Cirrhosis

## Methodology

1. Label Encoding
2. Train-Test Split
3. ANOVA F-Test Feature Selection
4. SMOTE-based Class Balancing
5. Model Training
6. Hold-Out Evaluation
7. 5-Fold Cross-Validation

## Best Results

Gradient Boosting achieved:

- Hold-Out Accuracy: 94.92%
- 5-Fold Cross-Validation Accuracy: 94.90 ± 1.63%
- MCC: 0.7348

## Dataset

https://archive.ics.uci.edu/dataset/571/hcv+data

## Repository Contents

- HepaStage_ANOVA_ML.ipynb : Complete implementation
- dataset.md : Dataset information
- requirements.txt : Required libraries
