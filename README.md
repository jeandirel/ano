# FIES Public-Use File Anonymization

This repository contains an extract of the **Family Income and Expenditure Survey (FIES)** public-use file for 2006. The data serves as a demonstration dataset for implementing microdata anonymization techniques.

The goal is to explore several approaches that reduce disclosure risk while retaining analytical utility. Planned notebooks will illustrate the following methods:

- **Recoding** – collapsing or generalizing categories to minimize uniqueness. *(See [`notebooks/recoding.ipynb`](notebooks/recoding.ipynb))*
- **Suppression** – removing or blanking out high-risk values. *(See [`notebooks/suppression.ipynb`](notebooks/suppression.ipynb))*
- **PRAM (Post-Randomization Method)** – probabilistic reclassification of categorical attributes. *(See [`notebooks/pram.ipynb`](notebooks/pram.ipynb))*
- **Micro-aggregation** – grouping records and replacing detailed values with group averages. *(See [`notebooks/micro_aggregation.ipynb`](notebooks/micro_aggregation.ipynb))*
- **Noise addition** – introducing small perturbations to numeric variables. *(See [`notebooks/noise_addition.ipynb`](notebooks/noise_addition.ipynb))*

These notebooks aim to demonstrate how the FIES public-use data can be anonymized using different strategies. The examples focus on education, experimentation and illustration rather than production-ready anonymization.
