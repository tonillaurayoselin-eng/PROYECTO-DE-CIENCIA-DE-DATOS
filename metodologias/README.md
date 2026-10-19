# Predicción de depresión: aplicación de cuatro metodologías de ciencia de datos

Proyecto de la E.E. **Metodología de la Investigación**
Facultad de Estadística e Informática, Universidad Veracruzana
Docente: Lorena López Lozada

## Descripción

Este trabajo aplica cuatro metodologías de ciencia de datos (TDSP, SEMMA, CRISP-DM y KDD) a problemas de predicción de depresión, con el fin de comparar cómo cada una organiza el proceso de análisis. Cada metodología cuenta con su propio reporte en PDF.

## Reportes

| # | Metodología | Modelo | Datos | Reporte |
|---|---|---|---|---|
| 1 | TDSP (Team Data Science Process) | Regresión logística | ECENASEM 2021 | [Ver PDF](01_TDSP_Reporte.pdf) |
| 2 | SEMMA | Regresión logística | ECENASEM 2021 | [Ver PDF](02_SEMMA_Reporte.pdf) |
| 3 | CRISP-DM | Regresión logística | ECENASEM 2021 | [Ver PDF](03_CRISP-DM_Reporte.pdf) |
| 4 | KDD | Árbol de decisión | Student Depression Dataset (Kaggle) | [Ver PDF](04_KDD_Reporte.pdf) |

> Los reportes 1 a 3 usan los mismos datos y el mismo modelo para comparar las metodologías en igualdad de condiciones. El reporte 4 es una aplicación distinta (otra población y otro modelo) y se incluye para mostrar el proceso KDD.

## Datos

- **ECENASEM 2021** (Evaluación Cognitiva del ENASEM), INEGI: 3,575 registros iniciales y 3,418 casos completos. Variable respuesta: síntomas depresivos con la escala CES-D.
- **Student Depression Dataset** (Santos, 2024), Kaggle: 27,901 registros iniciales y 27,896 tras la limpieza.

Los datos no se incluyen en este repositorio; se descargan de las fuentes originales.

## Herramientas

Python, pandas, statsmodels, scikit-learn, matplotlib y seaborn, ejecutados en Google Colab.
