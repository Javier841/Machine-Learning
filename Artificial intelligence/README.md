## Artificial Intelligence

En esta sección se exploran conceptos fundamentales de inteligencia artificial, con énfasis en técnicas de optimización evolutiva y modelos predictivos aplicados a problemas de regresión.

### Algoritmos genéticos

Uno de los enfoques principales es el uso de algoritmos genéticos, una técnica de optimización inspirada en los principios de la evolución natural. Estos algoritmos parten de una población inicial de soluciones generadas aleatoriamente, las cuales evolucionan a lo largo de múltiples generaciones mediante operadores de **mutación** y **cruce (crossover)**. En cada iteración, las soluciones se evalúan según una función de aptitud (fitness) y las mejores se seleccionan para reproducirse.

Este enfoque resulta especialmente útil cuando:

- No es posible calcular derivadas fácilmente
- El espacio de búsqueda es discreto o altamente complejo
- Se necesita evitar óptimos locales mediante exploración global del espacio de soluciones

La implementación se realiza con la librería **DEAP**, que proporciona un marco flexible para definir operadores genéticos, funciones de fitness y estrategias de selección.

### Árboles de regresión

Se abordan los árboles de regresión como modelos que permiten capturar relaciones no lineales entre variables mediante particiones sucesivas del espacio de características. A diferencia de los modelos lineales, los árboles no asumen una relación funcional específica, lo que los hace versátiles e interpretables para una amplia variedad de problemas de predicción.

### Regularización: Ridge y Lasso

Se estudian técnicas de regularización que penalizan la magnitud de los coeficientes del modelo para prevenir el sobreajuste. Ridge aplica una penalización L2 que reduce los coeficientes hacia cero sin eliminarlos, mientras que Lasso utiliza una penalización L1 que puede llevar algunos coeficientes exactamente a cero, funcionando como un método de selección de variables.

### Archivos

- `genetic-algorithms-with-deap.ipynb` — Implementación de algoritmos genéticos con DEAP
- `Regression_Trees.ipynb` — Árboles de regresión aplicados
- `Ridge_Lasso.ipynb` — Modelos de regularización
- `app.py` — Aplicación complementaria
- `RN.pdf` / `RN.tex` — Notas teóricas sobre redes neuronales
- `requirements.txt` — Dependencias del proyecto
