## Neural Networks

En esta sección se introduce el uso de redes neuronales artificiales para tareas de clasificación, utilizando Python y scikit-learn.

### Datos y visualización

Se trabaja con datos simulados generados mediante técnicas de clustering, lo que permite visualizar de forma intuitiva cómo los modelos aprenden a separar distintas clases en el espacio de características. Los datos se representan gráficamente con Matplotlib y Seaborn para entender la distribución y la complejidad del problema antes de entrenar cualquier modelo.

### Clasificador MLP

Se implementa un clasificador basado en redes neuronales (MLPClassifier) explorando diferentes arquitecturas mediante la variación del número de capas ocultas y neuronas por capa. Esto permite analizar cómo la complejidad de la red influye en su capacidad de aprendizaje y generalización.

Las redes utilizadas se basan en capas interconectadas donde cada una transforma la información de entrada hasta producir una predicción. Se emplea la **entropía cruzada** como función de pérdida, una métrica ampliamente utilizada en clasificación que cuantifica la diferencia entre las probabilidades predichas y las etiquetas reales.

### Hiperparámetros

Se analiza el impacto de parámetros clave en el entrenamiento:

- **Tasa de aprendizaje (learning rate)**: controla la velocidad con la que el modelo ajusta sus pesos en cada iteración
- **Número de iteraciones (epochs)**: cuántas veces el modelo recorre todo el dataset de entrenamiento
- **Tamaño y profundidad de la red**: número de capas y neuronas que determinan la capacidad del modelo

### Búsqueda de hiperparámetros

Se utilizan técnicas de validación y optimización para encontrar la mejor configuración del modelo:

- **Grid Search**: búsqueda exhaustiva sobre una grilla de combinaciones de hiperparámetros
- **Randomized Search**: búsqueda aleatoria que permite explorar un espacio más amplio de forma eficiente
- **Validación cruzada K-Fold**: evaluación robusta del modelo dividiendo los datos en K particiones para entrenar y validar iterativamente

### Notebooks

- `Neuronas.ipynb` — Clasificación con MLPClassifier, arquitecturas y búsqueda de hiperparámetros
- `Tiny_nn.ipynb` — Implementación de una red neuronal desde cero
- `utils.py` — Funciones auxiliares para visualización y evaluación
