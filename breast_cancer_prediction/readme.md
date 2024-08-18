# Breast Cancer Prediction Project

This project aims to predict breast cancer diagnosis using the Breast Cancer Wisconsin dataset from the UCI Machine Learning Repository. The project explores different models using Logistic Regression.

## Project Structure

- **breast_cancer.py**: Python script that implements three different Logistic Regression models:
  1. Using only the "radius_mean" feature.
  2. Using all available features.
  3. Using all available features with standard scaling.

## Overview

### Dataset
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)
- **Features**: Radius, Texture, Perimeter, Area, Smoothness, Compactness, Concavity, Concave Points, Symmetry, Fractal Dimension, and their statistical measures (mean, standard error, and worst).
- **Label**: Diagnosis (Benign = 0, Malignant = 1)

### Models Implemented
1. **Logistic Regression with "radius_mean"**:
   - Feature: radius_mean
   - Accuracy: 0.947368

2. **Logistic Regression with All Features**:
   - Features: All available features
   - Accuracy: 0.912281

3. **Logistic Regression with All Features (Standard Scaled)**:
   - Features: All available features (standard scaled)
   - Accuracy: 0.964912

## Installation and Usage

### Requirements
- Python 3.x
- Required packages: `pandas`, `missingno`, `scikit-learn`

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/basel5621/Grokking-machine-learning-projects.git
   cd Grokking-machine-learning-projects/breast_cancer_prediction
