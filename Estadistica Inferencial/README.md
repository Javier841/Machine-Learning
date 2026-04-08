## Estadística Inferencial

En esta sección se abordan conceptos de estadística inferencial mediante un enfoque teórico y práctico, utilizando Python para simulaciones, estimación de parámetros y pruebas de hipótesis.

---

### Modelos de distribución

Se analiza una muestra aleatoria cuya función de densidad pertenece a la familia de distribuciones Beta. Utilizando NumPy, Matplotlib y SciPy se generan muestras aleatorias, se visualizan funciones de densidad y se estudia el comportamiento de la distribución bajo distintos parámetros.

---

### Simulación de distribuciones

Se realizan simulaciones con distribuciones de la familia exponencial para estudiar empíricamente propiedades estadísticas fundamentales:

- Distribución t de Student
- Distribución Beta
- Distribución Lognormal
- Distribución Gamma
- Distribución Poisson
- Distribución Exponencial

A través de estas simulaciones se observa la evolución de la media muestral conforme aumenta el tamaño de muestra, mostrando de forma empírica la convergencia hacia la media teórica, lo cual ilustra la Ley de los Grandes Números.

---

### Estimación por Máxima Verosimilitud (MLE)

Se estudia el método de Máxima Verosimilitud para estimar parámetros de un modelo. Dado un modelo probabilístico y una muestra observada, se construye la función de verosimilitud, se obtiene la log-verosimilitud y se encuentra el estimador que maximiza la probabilidad de haber observado los datos. Se verifica la condición de máximo mediante la segunda derivada.

---

### Pruebas de hipótesis

Se implementan pruebas de hipótesis estadísticas para evaluar afirmaciones sobre parámetros poblacionales a partir de datos muestrales, incluyendo la formulación de hipótesis nula y alternativa, el cálculo de estadísticos de prueba y la interpretación de p-values.

---

### Notebooks

- `Solución_Pruebas_de_hipótesis.ipynb` — Pruebas de hipótesis resueltas
- `UMVUE_beta.ipynb` — Estimadores UMVUE y distribución Beta
- `data.html` — Datos complementarios
