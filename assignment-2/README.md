# Assignment 2 - Histograms, Kernel Density, and Unsupervised Methods

This folder contains the materials for Practical Assignment 2 of the Programming
Workshop course at the University of Buenos Aires.

---

## Overview

The assignment continues the analysis of the Permanent Household Survey (EPH), extending
the cleaned dataset from Assignment 1 with new indicators and exploratory methods.

The project applies distributional analysis and unsupervised learning techniques to
compare selected EPH samples.

---

## Main Objectives

- Consolidate a homogeneous dataset for 2005Q1 and 2025Q1.
- Create derived variables such as squared age, years of education, and working hours.
- Analyze distributions using histograms and kernel density estimates.
- Apply principal component analysis.
- Apply clustering methods, including k-means and hierarchical clustering.

---

## Repository Structure

```text
assignment-2/
|
|-- data/       # Cleaned and auxiliary datasets
|-- docs/
|   |-- materials/
|   `-- report/
|-- figures/    # Generated figures
|-- scripts/    # Source code and notebooks
`-- README.md
```

---

## Environment

The project was developed in Python 3.10 or later.

Install the required dependencies with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn kmodes
```

---

## Academic Context

Practical assignment developed for the Programming Workshop course, Master's Program in
Applied Economics, University of Buenos Aires.
