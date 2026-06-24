# Presentation 1 - Exploratory Analysis of EMSE 2018

**Course:** Programming Workshop  
**Program:** Master's Program in Applied Economics, University of Buenos Aires  
**Group 15:** Julián Delgadillo Marín, Alejandro Alcocer, Christian Campos  
**Date:** November 5, 2025

---

## Overview

This folder contains the materials for the first group presentation in the Programming
Workshop course.

The project developed an exploratory analysis of the **Global School-based Student
Health Survey (EMSE 2018)**, focusing on healthy habits and risk behaviors among
school-aged adolescents in Argentina.

The presentation was prepared in **Beamer (LaTeX)** and included data processing,
visualization, and the development of research hypotheses for the final course
application.

---

## Folder Structure

```text
exposicion-1/
|
|-- data/          # Dataset source and download notes
|-- Graficos/       # PNG figures used in the presentation
|-- Presentacion/   # Beamer source and PDF files
|-- Codigo/         # Auxiliary cleaning and visualization scripts
`-- README.md
```

---

## Data Source

The analysis uses the **Global School-based Student Health Survey (EMSE 2018)**.

Source: Ministry of Health of Argentina  
Open Data Portal:

<https://datos.gob.ar/dataset/salud-base-datos-3deg-encuesta-mundial-salud-escolar-emse-con-resultados-nacionales-argentina>

The original CSV file is larger than 100 MB and is therefore not included directly in
the repository. It can be downloaded from the official source.

---

## Presentation Contents

- General description of the EMSE 2018 dataset.
- Distribution by sex and age.
- Healthy habits, including physical activity and nutrition.
- Risk behaviors, including tobacco and alcohol consumption.
- Research and modeling proposals for the final course application.
- Possible use of supervised classification models such as Logit and KNN.

---

## Academic Objective

The presentation integrates core course skills:

1. Data cleaning and structuring.
2. Reproducible visualization.
3. Research hypothesis generation.
4. Initial predictive modeling design using real national microdata.

---

## Tools

- Python: `pandas`, `matplotlib`, `seaborn`
- LaTeX Beamer for academic presentation
- GitHub for version control and group documentation

---

## License

This material is shared for educational purposes under a CC BY-NC-SA 4.0 license. The
data belong to the Ministry of Health of Argentina.
