# Mathematical Foundations, Comparison and Validation of Credit Risk Models

This repository contains a technical report implemented in a Jupyter Notebook. It compares a baseline logistic regression, a multivariable logistic regression, a probit regression and a shallow decision tree using reproducible synthetic credit data.

## Main Objectives

- analyse borrower characteristics using descriptive statistics;
- compare defaulted and non-defaulted observations;
- explain the mathematical foundations of logistic and probit regression;
- assess model discrimination, probability accuracy, calibration and overfitting;
- compare alternative modelling approaches;
- select a preferred model using multiple validation criteria.

## Models Included

The project compares the following models:

1. Baseline logistic regression using debt-to-income ratio only;
2. Multivariable logistic regression;
3. Probit regression;
4. Shallow decision tree as a nonlinear benchmark.

## Main Deliverable

The main analysis is available in:

`credit_default_model_comparison.ipynb`

## Reproducibility

The project was developed and tested with Python 3.14.7.

The required package versions are listed in `requirements.txt`.

To reproduce the analysis:

1. Create and activate a Python virtual environment.
2. Install the required packages:

   `python -m pip install -r requirements.txt`

3. Open `credit_default_model_comparison.ipynb` in a Jupyter-compatible environment, such as Visual Studio Code or JupyterLab.

4. Restart the kernel and run all cells from top to bottom.

A fixed random seed of 42 is used for synthetic data generation, the train-test split and model configuration. This supports reproducibility of the sample and analytical results.

## Important Limitation

All observations used in this project are synthetic. The analysis is intended for educational purposes and does not represent a production credit risk model, a real credit portfolio, or the methodology of any financial institution.
