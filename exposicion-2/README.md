# Presentation 2 - Critical Risk Prediction in Students

Presentation 2 for the Programming Workshop course at the University of Buenos Aires.

---

## Project Overview

This folder contains code, results, and visualizations for a machine learning analysis
based on the Global School-based Student Health Survey (EMSE).

The main goal is to identify students at critical risk using supervised classification
models, prioritizing early detection by reducing false negatives.

---

## Analysis Objective

The project evaluates several classification models and compares them using:

- Sensitivity or recall.
- Precision.
- Classification errors.
- Confusion matrices.
- Permutation importance.

The preferred model is the one that minimizes false negatives, given the social and
epidemiological relevance of failing to detect students at risk.

---

## Dataset

The analysis uses a preprocessed subset of the EMSE survey with demographic, behavioral,
school-related, and family-related variables.

Variables directly linked to the target outcome, such as alcohol, tobacco, and injuries,
were excluded to avoid data leakage.

---

## Models Evaluated

The project compares three main models:

- Naive Bayes (`CategoricalNB`)
- Pruned decision tree
- Logistic regression

Each model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

---

## Selected Model

Naive Bayes was selected because it achieved the highest recall and the lowest number of
false negatives among the models evaluated.

The model aligns with the central objective of maximizing the detection of students at
critical risk.

---

## Visual Outputs

The project includes:

- Labeled confusion matrices.
- Top feature importance plots derived from permutation importance.
- Visual summaries of the most relevant predictors.

Relevant predictors include sex, physical inactivity, age, school grade, and nutritional
habits.

---

## Repository Structure

```text
exposicion-2/
|
|-- data/
|-- docs/
|-- figures/
|-- scripts/
`-- README.md
```

---

## Requirements

Install the required Python dependencies with:

```bash
pip install numpy pandas scikit-learn seaborn matplotlib
```

---

## How to Run

1. Open the notebooks in Jupyter Notebook or Google Colab.
2. Run the cells in order.
3. Review preprocessing, model training, comparison, model selection, and visual outputs.

---

## Authors

- Christian Campos
- Julián Delgadillo Marín
- Alejandro Alcocer

Year: 2025
