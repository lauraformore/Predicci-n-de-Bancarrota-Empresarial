# Predicción de Bancarrota Empresarial
***Análisis de Solvencia Corporativa y Riesgo Financiero con Machine Learning***

::::{grid} 1 1 3 3
:gutter: 2

:::{grid-item-card} Asignatura
:class-card: meta-card
Visualización de Datos y Machine Learning
:::

:::{grid-item-card} Autoras
:class-card: meta-card
Laura Rivera & Natalý Cárdenas
*Universidad del Norte*
:::

:::{grid-item-card} Metodología
:class-card: meta-card
EDA · Feature Engineering · Modelos de Clasificación
:::

::::

:::{important} Resumen del Proyecto
Este estudio aplica técnicas de Machine Learning sobre un conjunto de indicadores financieros corporativos para predecir la probabilidad de insolvencia y quiebra empresarial. A través de un análisis exploratorio de datos (EDA) exhaustivo, técnicas de rebalanceo y evaluación de modelos de clasificación, se identifican las variables críticas de riesgo financiero y solvencia.
:::

## Estructura del Análisis

::::{grid} 1 1 2 2
:gutter: 2

:::{grid-item-card} 1. Análisis Exploratorio (EDA)
:class-card: step-card
Evaluación de distribuciones, tratamiento de valores faltantes, detección de sesgo y análisis de correlación entre variables financieras.
:::

:::{grid-item-card} 2. Modelado y Predicción
:class-card: step-card
Entrenamiento de algoritmos supervisados, optimización de hiperparámetros y evaluación de métricas orientadas a la detección de riesgo (Recall / ROC-AUC).
:::

::::

:::{tip} ¿Qué encontrarás aquí?
Un recorrido por el análisis exploratorio de datos, la construcción de modelos predictivos y las visualizaciones clave que explican el comportamiento financiero de las empresas en riesgo.
:::


**Pasos de este notebook:**

1. Eliminar la variable constante (`Net Income Flag`)
2. Estandarizar las variables numéricas
3. Balancear las clases (`class_weight='balanced'`)
4. Entrenar el modelo
5. Evaluar con las métricas correctas para clases desbalanceadas
