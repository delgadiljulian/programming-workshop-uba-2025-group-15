# 📘 Predicción de Riesgo Crítico en Estudiantes mediante Modelos de Machine Learning
Exposición #2 – Taller de Programación (UBA)
# 📌 Descripción del Proyecto

Este repositorio contiene el código, resultados y visualizaciones correspondientes a la Exposición #2 del Taller de Programación (UBA).
El objetivo principal del trabajo es identificar estudiantes en riesgo crítico a partir de datos de la Encuesta Mundial de Salud Escolar (EMSE), utilizando técnicas de Machine Learning y priorizando la detección temprana mediante la reducción de falsos negativos (FN).

# 🎯 Objetivo del Análisis

Entrenar distintos modelos supervisados de clasificación.

Compararlos en términos de sensibilidad (Recall), precisión y errores de clasificación.

Seleccionar el modelo con menor cantidad de falsos negativos, dada su importancia social y epidemiológica.

Interpretar los factores asociados al riesgo mediante Permutation Importance.

Visualizar resultados clave mediante matrices de confusión y gráficos de importancia.

# 📊 Dataset

Se utiliza un subconjunto preprocesado de la Encuesta Mundial de Salud Escolar (EMSE) con variables:

Demográficas (edad, sexo, escolaridad)

Conductuales (actividad física, hábitos alimentarios)

Escolares y familiares

Variables trivialmente asociadas al riesgo (alcohol, tabaco, lesiones) fueron excluidas para evitar data leakage.

# 🤖 Modelos Evaluados

Se entrenaron y evaluaron tres modelos principales:

Naive Bayes (CategoricalNB)

Árbol de Decisión Podado

Regresión Logística (Logit)

Cada modelo fue evaluado con:

Accuracy

Precision

Recall (Sensibilidad)

F1-Score

Matriz de confusión (TP, FP, TN, FN)

# 🏆 Modelo Ganador: Naive Bayes

Naive Bayes fue seleccionado porque:

Obtuvo el mayor Recall (0.604)

Presentó la menor cantidad de Falsos Negativos (FN = 3009)

Cumple el objetivo central del proyecto: maximizar la detección de estudiantes en riesgo crítico

Resumen de métricas del modelo ganador
Métrica	Valor
Accuracy	~0.615
Precision	~0.562
Recall (Sensibilidad)	0.604
F1-Score	~0.583
Falsos Negativos (FN)	3009
# 🔥 Resultados Visuales Incluidos
✔ Matriz de Confusión rotulada (TN, FP, FN, TP)

Facilita la interpretación del impacto de los falsos negativos.

✔ Gráfico Top 10 de Variables Importantes

Derivado de Permutation Importance.

Las variables más relevantes incluyen:

Sexo (Femenino/Masculino)

Actividad física (“Nunca”)

Edad y curso escolar

Hábitos alimentarios

# 🧠 Interpretación de Importancia de Variables

El modelo identifica como predictores relevantes:

Género: patrones diferenciales entre grupos.

Inactividad física: indicador fuerte de vulnerabilidad.

Edad y escolaridad: etapas críticas de la adolescencia.

Hábitos alimentarios: reflejan organización y entorno familiar.

Estas variables funcionan como indicadores estructurales del contexto psicosocial del estudiante.

📁 Estructura del Repositorio
📁 Datos/
📁 Docs/
📁 Figuras/
📁 Scripts/
README.md

# 🧪 Requisitos

Instalación de dependencias:

pip install numpy pandas scikit-learn seaborn matplotlib

# 🚀 Cómo Ejecutar el Proyecto

Clonar el repositorio

Abrir los notebooks en Jupyter o Google Colab

Ejecutar las celdas en orden:

Preprocesamiento

Entrenamiento de modelos

Comparación

Selección del modelo ganador

Visualizaciones

# 📘 Conclusiones

Naive Bayes fue el modelo más adecuado para el objetivo de minimizar falsos negativos.

Su simplicidad no impide un buen desempeño en la detección de riesgo.

Los resultados permiten identificar patrones destacados para futuros análisis y políticas educativas/sanitarias.

# 👥 Autores

Christian Campos
Julián Delgadillo Marín
Alejandro Alcocer
Año: 2025 — Cuatrimestre IV
