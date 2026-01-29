# Bank-Fraud-Detection-using-Unsupervised-Machine-Learning
Este proyecto aplica técnicas de Machine Learning No Supervisado para la detección de fraude en cuentas bancarias. Utilizando el dataset BAF (publicado en NeurIPS 2022), el objetivo es identificar comportamientos anómalos y subgrupos de transacciones que presentan patrones sospechosos, permitiendo una prevención proactiva del fraude.


# Bank Fraud Detection using Unsupervised Machine Learning

## Descripción
Este proyecto aplica técnicas de **Machine Learning No Supervisado** para la detección de fraude en cuentas bancarias. Utilizando el dataset BAF (publicado en NeurIPS 2022), el objetivo es identificar comportamientos anómalos y subgrupos de transacciones que presentan patrones sospechosos, permitiendo una prevención proactiva del fraude.

## Stack Tecnológico
* **Algoritmo:** K-Means Clustering.
* **Librerías:** Scikit-learn, Pandas, NumPy.
* **Visualización:** Seaborn, Matplotlib (Análisis 2D y 3D).
* **Métricas de Selección:** Método del Codo (Elbow Method) para la optimización de hiperparámetros (k).

## Innovaciones y Análisis Técnico
* **Identificación de Patrones Ocultos:** A través de un análisis comparativo, se determinó que k=4 es la segmentación óptima. Este ajuste permitió descubrir una sub-estructura oculta dentro de los datos que no era visible con agrupaciones menores, lo que podría representar modalidades de fraude sofisticadas.
* **Segmentación de Riesgo:** El modelo logra aislar grupos con características constantes y bien definidas, facilitando el análisis forense de transacciones financieras.
* **Enfoque en Datos Sintéticos Reales:** Trabajo con el dataset BAF, un estándar en la investigación actual de fraude bancario presentado en NeurIPS.

## Graficas de clusteres y metodo del codo
<img width="788" height="349" alt="image" src="https://github.com/user-attachments/assets/173ca46d-ef48-4ffc-bea5-9e732f45e373" />
<img width="631" height="451" alt="image" src="https://github.com/user-attachments/assets/fa012808-6ea9-4f40-953c-67772608f12e" />
<img width="813" height="659" alt="image" src="https://github.com/user-attachments/assets/608bcd37-56cf-4cc5-980a-bf7f6e3d2451" />


## Cómo empezar
1.  Clonar el repositorio.
2.  Instalar dependencias: `pip install scikit-learn pandas matplotlib seaborn`
3.  Ejecutar el notebook `Caso Practico Final Modulo ML.ipynb`.
