# Assignment 1 - First Exploration of the EPH

This folder contains the materials for Practical Assignment 1 of the Programming
Workshop course at the University of Buenos Aires.

---

## General Objective

The assignment introduces the **Permanent Household Survey (EPH)**. It focuses on data
cleaning, descriptive analysis, and poverty measurement by comparing the years **2005**
and **2025**.

---

## Contents

- `scripts/assignment-1-group-15.ipynb`: main notebook with code and figures.
- `docs/report/assignment-1-group-15-report.pdf`: final report in PDF format.
- `data/`: EPH microdata and supporting tables.
- `docs/materials/`: supporting course material and reference documents.
- `figures/`: generated figures.

The full `usu_individual_T105.dta` file is larger than 25 MB and should be downloaded
from the official INDEC website:

<https://www.indec.gob.ar/indec/web/Institucional-Indec-BasesDeDatos>

---

## Workflow

1. Download and merge EPH datasets for 2005 and 2025.
2. Clean missing values, formats, and outliers.
3. Perform exploratory analysis using descriptive plots and summary statistics.
4. Measure poverty using household income requirements and household classification.

---

## Minimum Required Variables

`CH04`, `CH06`, `CH07`, `CH08`, `NIVEL_ED`, `ESTADO`, `CAT_INAC`, `IPCF`, `ITF`,
`REGION`, `CODUSU`, `NRO_HOGAR`.

---

## Academic Context

Practical assignment developed for the Programming Workshop course, Master's Program in
Applied Economics, University of Buenos Aires.
