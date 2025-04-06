# Applied Machine Learning Course

This repository contains coursework for the Applied Machine Learning course, focusing on implementing and analyzing various machine learning techniques.

## Contents

### Week 4 - Binary Classification
- [Binary_Classifier.ipynb](Binary_Classifier.ipynb): Implementation of a binary classifier for exoplanet detection using the Kepler dataset
    - Uses SGDClassifier with hyperparameter tuning
    - Includes ROC curve analysis and threshold optimization
    - Demonstrates metrics evaluation (accuracy, precision, recall, F1)

### Week 5 - Regression Analysis
- [Tricky_Regression.ipynb](Tricky_Regression.ipynb): Exploration of regression techniques for sigmoid function data
    - Compares clean vs. noisy data modeling
    - Implements polynomial regression with various degrees
    - Analyzes model performance with and without regularization
    - Visualizes training vs. test errors for different model complexities

### Week 8 - ML Performance Optimization
- [ML_on_a_budget.ipynb](ML_on_a_budget.ipynb): Analyzing machine learning performance with limited resources
    - Compares different classification approaches on the MNIST dataset
    - Examines training time and accuracy tradeoffs
    - Includes experiment framework for benchmarking SVC vs OneVsRest approaches
    - Visualizes performance metrics across different training set sizes

## Setup

Each notebook is self-contained with necessary imports. The code requires standard data science libraries:
- scikit-learn
- pandas
- numpy
- matplotlib

## Usage

Open the Jupyter notebooks in your preferred environment. The notebooks include detailed comments and explanations alongside the code.