## Curso Machine Learning

En esta sección se desarrollan modelos y técnicas fundamentales de machine learning, combinando teoría con implementaciones prácticas en Python aplicadas a datasets reales.

Se cubren problemas de regresión, clasificación, reducción de dimensionalidad y predicción de series temporales, permitiendo entender cómo aplicar algoritmos de aprendizaje automático en distintos escenarios.

---

### Regresión lineal y múltiple

Se trabaja con datasets como **50 Startups** y **advertising** para implementar modelos de regresión lineal simple y múltiple. El objetivo es analizar la relación entre variables independientes y predecir valores continuos, evaluando el ajuste del modelo mediante métricas como R², error cuadrático medio y análisis de residuos.

---

### Clasificación con regresión logística

Se implementa regresión logística utilizando scikit-learn para resolver problemas de clasificación binaria. Este modelo permite estimar la probabilidad de pertenencia a una clase a partir de las variables de entrada, siendo uno de los métodos más utilizados como baseline en problemas de clasificación.

---

### Reducción de dimensionalidad

Se estudian técnicas para reducir la cantidad de variables manteniendo la mayor cantidad de información posible:

- **PCA (Análisis de Componentes Principales)**: técnica no supervisada que transforma los datos a un espacio de menor dimensión conservando la mayor varianza. Se analiza cómo el número de componentes afecta el rendimiento del modelo y se visualizan los datos proyectados.
- **LDA (Análisis Discriminante Lineal)**: técnica supervisada que busca maximizar la separabilidad entre clases, reduciendo dimensiones mientras mejora la capacidad discriminativa del modelo.
- **QDA (Análisis Discriminante Cuadrático)**: extensión de LDA que permite fronteras de decisión no lineales al estimar una matriz de covarianza por cada clase.

---

### Regularización: Ridge y Lasso

Se implementan modelos lineales regularizados que penalizan la magnitud de los coeficientes para prevenir el sobreajuste. Se compara el comportamiento de Ridge (penalización L2) y Lasso (penalización L1) y se analiza cómo el parámetro de regularización afecta la complejidad del modelo.

---

### Series temporales con LSTM

Se introduce el uso de redes neuronales recurrentes LSTM (Long Short-Term Memory) para la predicción de precios de acciones. Este enfoque captura dependencias temporales en datos secuenciales, siendo especialmente adecuado para series de tiempo financieras donde los patrones históricos influyen en valores futuros.

---

### Notebooks

- `regresion_01.ipynb` — Regresión lineal simple
- `Ejemplo_de_regresión_múltiple.ipynb` — Regresión lineal múltiple
- `Regresion_logistica.ipynb` — Clasificación con regresión logística
- `PCA_ejemplo.ipynb` — Ejemplo introductorio de PCA
- `PCA_Implementacion.ipynb` — Implementación completa de PCA
- `PCA y Regresión.ipynb` — Combinación de PCA con modelos de regresión
- `LDA_01.ipynb` — Análisis Discriminante Lineal
- `QDA.ipynb` — Análisis Discriminante Cuadrático
- `Ridge_Lasso.ipynb` — Regularización Ridge y Lasso
- `Ridge_regresion-1.ipynb` — Regresión Ridge aplicada
- `LSTM.ipynb` — Predicción de series temporales con LSTM
- `Multiple Linear Regression Exercise Solution.ipynb` — Ejercicio resuelto de regresión múltiple
