# Structural Equation Modeling (SEM) with Python
This repository provides a Python implementation of Structural Equation Modeling (SEM) using the `semopy` library. SEM is a powerful statistical technique that allows for the analysis of complex relationships between observed and latent variables.

The exercises and data used in this repository were kindly provided by [Dr. Maffezzolli](https://www.pucpr.br/escola-de-negocios/docente/eliane-cristine-francisco-maffezzolli/).
## Installation
All dependencies are listed in the `Pipfile` file. You can install them using pipenv:

```bash
pip install pipenv
pipenv install
```

In order to render the graphs, you will also need to install `graphviz` on your system. You can find installation instructions [here](https://graphviz.gitlab.io/download/).

## Practical Exercises

All results presented in this repository were validated against the results obtained in SPSS AMOS, you may find the AMOS output files in the `validation/amos_outputs` directory.

- [Practice 0 - Partial Measurement Model](Practice%200/practice_0.ipynb)
- [Practice 1 – Full Measurement Model CFA](Practice%201/practice_1.ipynb)
- [Practice 2 – Structural Model: Hypothesis Testing](Practice%202/practice_2.ipynb)
- [Practice 3 – Multi-Group Analysis](Practice%203/practice_3.ipynb)

## Theory
- Confirmatory Factor Analysis (CFA)
  - [CFA Cutoff Criteria](CFA%20Cut-offs.md)
- Structural Model
  - **Variance Explained ($R^2$):** 
    - Hayes, T. (2021). R-squared change in structural equation models with latent variables and missing data. Behavior Research Methods, 53(5), 2127–2157. https://doi.org/10.3758/s13428-020-01532-y
  - **Indirect Effects**: 
    - Abu-Bader, S., & Jones, T. V. (2021). Statistical mediation analysis using the Sobel test and Hayes SPSS Process Macro. International Journal of Quantitative and Qualitative Research Methods, 9(1), 42–61.
- Multi-Group Analysis
  - **Comparing group regression coeficients:** 
    - Clogg, C. C., Petkova, E., & Haritou, A. (1995). Statistical methods for comparing regression coefficients between models. American Journal of Sociology, 100(5), 1261–1293. https://doi.org/10.1086/230638
