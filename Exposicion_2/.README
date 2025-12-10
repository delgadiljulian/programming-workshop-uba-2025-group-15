README – Predicción de Riesgo Crítico en Estudiantes mediante Modelos de Machine Learning
📌 Descripción del Proyecto

Este repositorio contiene el código, resultados y visualizaciones correspondientes a la Exposición #2 del Taller de Programación (UBA).
El objetivo principal del trabajo es identificar estudiantes en riesgo crítico a partir de datos de la Encuesta Mundial de Salud Escolar (EMSE), utilizando técnicas de Machine Learning y priorizando la detección temprana mediante la reducción de falsos negativos (FN).

🎯 Objetivo del Análisis

Entrenar distintos modelos supervisados de clasificación.

Compararlos en términos de sensibilidad (Recall), precisión y errores de clasificación.

Seleccionar el modelo con menor cantidad de falsos negativos, dada su importancia social y epidemiológica.

Interpretar los factores asociados al riesgo mediante Permutation Importance.

Visualizar resultados clave mediante matrices de confusión y gráficos de importancia.

📊 Dataset

Se utiliza un subconjunto preprocesado de la Encuesta Mundial de Salud Escolar (EMSE) con variables:

Demográficas (edad, sexo, escolaridad)

Conductuales (actividad física, hábitos alimentarios)

Escolares y familiares

Variables trivialmente asociadas al riesgo (alcohol, tabaco, lesiones) fueron excluidas para evitar data leakage.

🤖 Modelos Evaluados

Se entrenaron y evaluaron tres modelos principales:

Naive Bayes (CategoricalNB)

Árbol de Decisión Podado

Regresión Logística (Logit)

Cada modelo fue evaluado con las métricas:

Accuracy

Precision

Recall (Sensibilidad)

F1-Score

Matriz de confusión (TP, FP, TN, FN)

🏆 Modelo Ganador: Naive Bayes

Naive Bayes fue seleccionado por:

Obtener el mayor Recall (Sensibilidad)

Presentar la menor cantidad de Falsos Negativos (FN)

Cumplir el objetivo central del proyecto: maximizar la detección de estudiantes en riesgo crítico

Resumen de métricas del modelo ganador:

Métrica	Valor
Accuracy	~0.615
Precision	~0.562
Recall (Sensibilidad)	0.604
F1-Score	~0.583
Falsos Negativos (FN)	3009
🔥 Resultados Visuales Incluidos
✔ Matriz de Confusión rotulada (TN, FP, FN, TP)

La matriz incluye etiquetas explícitas para facilitar la interpretación del impacto de los falsos negativos.

✔ Gráfico Top 10 de Variables Importantes

A partir de Permutation Importance, se identifican las variables que más influyen en la predicción:

Sexo (femenino/masculino)

Actividad física (especialmente “Nunca”)

Edad y curso escolar

Hábitos alimentarios

🧠 Interpretación de Importancia de Variables

El modelo identifica como predictores relevantes:

Género: diferencias conductuales y sociales entre grupos.

Inactividad física: fuertemente asociada al riesgo.

Edad y escolaridad: reflejan etapas vulnerables de la adolescencia.

Hábitos alimentarios: indicadores indirectos del contexto familiar.

Estas variables no implican causalidad, sino que funcionan como señales indirectas del entorno psicosocial del estudiante.

📁 /src
    ├── preprocesamiento.ipynb
    ├── modelos.ipynb
    ├── visualizaciones.ipynb
📁 /figuras
    ├── matriz_confusion_nb.png
    ├── top10_importancia_nb.png
📁 /data
    ├── emse_preprocesado.csv
README.md

🧪 Requisitos

Instalación de dependencias:

pip install numpy pandas scikit-learn seaborn matplotlib

🚀 Cómo Ejecutar el Proyecto

Clonar el repositorio

Abrir el notebook principal en Jupyter o Colab

Ejecutar las celdas paso a paso:

Preprocesamiento

Entrenamiento de modelos

Comparación

Selección del modelo ganador

Generación de visualizaciones

📘 Conclusiones

Naive Bayes demostró ser el modelo más adecuado para el objetivo del proyecto.

Su fortaleza radica en la capacidad de identificar efectivamente estudiantes en riesgo.

A pesar de su simplicidad, muestra un desempeño competitivo y fácilmente interpretable.

La importancia de variables revela patrones relevantes para futuras intervenciones educativas y de salud.

📎 Contacto / Créditos

Trabajo realizado para la Exposición 2 – Taller de Programación (UBA).
Autor: Christian Campos, Julián Delgadillo Marín, Alejandro Alcocer
Año: 2025-IV
