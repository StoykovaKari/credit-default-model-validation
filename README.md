# Mathematical Foundations and Validation of Credit Risk Models

This repository contains a technical report implemented in a Jupyter Notebook. The project compares a baseline logistic regression, a multivariable logistic regression, a probit regression, and a shallow decision tree using reproducible synthetic credit data.

## Main Objectives

- Analyse borrower characteristics using descriptive statistics.
- Compare defaulted and non-defaulted borrowers through statistical tests and effect size measures.
- Explain the mathematical foundations of logistic and probit regression.
- Assess model discrimination, probability accuracy, calibration, and overfitting.
- Compare alternative modelling approaches.
- Select a preferred model using multiple validation criteria.

## Models Included

The project evaluates the following models:

1. Baseline logistic regression using only the debt-to-income ratio (DTI).
2. Multivariable logistic regression.
3. Probit regression.
4. Shallow decision tree as a nonlinear benchmark.

## Main Deliverable

The complete analysis is available in:

`credit_default_model_comparison.ipynb`

The notebook includes the theoretical background, mathematical derivations, Python implementation, model validation, results, references, and self-assessment.

## Reproducibility

The project was developed and tested using Python 3.14.7.

The required package versions are listed in:

`requirements.txt`

To reproduce the analysis:

1. Create and activate a Python virtual environment.
2. Install the required packages:

```bash
python -m pip install -r requirements.txt
```

3. Open `credit_default_model_comparison.ipynb` in a Jupyter-compatible environment such as JupyterLab, Visual Studio Code, or Jupyter Notebook.
4. Select **Kernel → Restart & Run All** to execute the notebook from beginning to end.

A fixed random seed (`42`) is used for synthetic data generation, the train-test split, and model configuration. This ensures that the dataset and analytical results can be reproduced consistently.

## Important Limitation

All observations used in this project are synthetic. The analysis is intended for educational purposes and does not represent a production credit risk model, a real credit portfolio, or the methodology of any financial institution.

## Author

**Karamfila Stoykova**

Final Project for **Math Concepts for Developers**  
SoftUni, 2026
