# 📡 TelecomX: Predicción de Churn y Estrategia de Retención de Clientes

## 📋 Descripción del Proyecto
Este proyecto aborda uno de los mayores desafíos en la industria de las telecomunicaciones: la **fuga de clientes (Churn)**. El objetivo principal fue identificar proactivamente a los clientes con alta probabilidad de abandonar **TelecomX** para diseñar estrategias de retención basadas en datos.

A través de un flujo completo de Data Science, se analizaron factores demográficos, servicios contratados y comportamiento de facturación para entrenar modelos predictivos capaces de "levantar la mano" antes de que el cliente decida irse.

## 🧠 Modelos Implementados
Se evaluaron y compararon diversas arquitecturas para encontrar el equilibrio entre precisión y capacidad de detección (Recall):

1.  **Regresión Logística (Ganador):** Seleccionado para producción por su alta explicabilidad y un **Recall del 52.13%**.
2.  **Random Forest:** Utilizado para identificar la jerarquía de importancia de las variables.
3.  **K-Nearest Neighbors (KNN):** Para análisis de segmentación por proximidad de perfiles.
4.  **SVM (Support Vector Machines):** Para entender fronteras de decisión complejas.

## 📊 Hallazgos Clave (Insights de Negocio)
* **Contratos Mes a Mes:** Son el principal disparador de fuga. Representan la mayor volatilidad de la cartera.
* **Antigüedad (Tenure):** Los primeros 6 meses son críticos; si el cliente supera este periodo, su probabilidad de abandono cae drásticamente.
* **Fibra Óptica y Costos:** Existe una sensibilidad alta al precio en servicios de alta gama, lo que sugiere una oportunidad para mejorar la percepción de valor.

## 🚀 Resultados del Modelo Seleccionado
El modelo de **Regresión Logística** arrojó los siguientes resultados en el conjunto de prueba:

| Métrica | Valor |
| :--- | :--- |
| **Precision** | 63.51% |
| **Recall (Sensibilidad)** | 52.13% |
| **F1-Score** | 57.26% |

> **Impacto:** Somos capaces de identificar correctamente a más de la mitad de los clientes que se van a fugar, permitiendo al equipo de Marketing actuar con una precisión del 63%.

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Python 3.x
* **Librerías:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn.
* **Entorno:** Jupyter Notebook / Google Colab.

## 📂 Estructura del Repositorio
* `Challenge_ONE_Data_Science_Telecom_X.ipynb`: Notebook con el análisis exploratorio, preprocesamiento y entrenamiento.
*
