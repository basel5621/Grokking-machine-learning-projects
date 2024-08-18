# Fuel Efficiency Prediction Project

This project aims to predict fuel efficiency (MPG) using various features of automobiles like Weight, Horsepower, Cylinders, etc., based on the Auto MPG dataset from the UCI Machine Learning Repository.

## Project Structure

- **fuel_efficiency_project.py**: Python script that implements various Linear Regression models (single-variable, multi-variable, and normalized multi-variable) to predict MPG.

## Overview

### Dataset
- **Source**: [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/auto+mpg)
- **Features**: Cylinders, Displacement, Horsepower, Weight, Acceleration, Model Year, Origin
- **Label**: MPG (Miles Per Gallon)

### Models Implemented
1. **Single-variable Linear Regression**:
   - Feature: Weight
   - Score: 0.693

2. **Single-variable Linear Regression with Horsepower**:
   - Feature: Horsepower
   - Score: 0.57

3. **Multi-variable Linear Regression**:
   - Features: All available features
   - Score: 0.81

4. **Normalized Multi-variable Linear Regression**:
   - Features: All available features (normalized)
   - Score: 0.842

## Installation and Usage

### Requirements
- Python 3.x
- Required packages: `matplotlib`, `numpy`, `pandas`, `seaborn`, `scikit-learn`

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/basel5621/Grokking-machine-learning-projects.git
   cd Grokking-machine-learning-projects/fuel_efficiency
