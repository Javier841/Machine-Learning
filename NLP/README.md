## NLP

En esta sección se abordan técnicas fundamentales de Procesamiento de Lenguaje Natural, enfocadas en la representación, transformación y análisis de datos textuales con Python.

El texto es uno de los tipos de datos más comunes en ciencia de datos, y a partir de cadenas de caracteres se aplican distintas técnicas para extraer información relevante y convertir el lenguaje natural en representaciones que puedan ser procesadas por modelos computacionales.

---

### Modelos de representación de texto

Se estudian métodos que permiten identificar temas latentes dentro de colecciones de documentos:

- **LSI (Latent Semantic Indexing)**: descompone la matriz término-documento para encontrar patrones semánticos ocultos, reduciendo la dimensionalidad del espacio de representación.
- **LDA (Latent Dirichlet Allocation)**: modelo probabilístico que asume que cada documento es una mezcla de temas, y cada tema es una distribución de palabras. Permite descubrir la estructura temática de un corpus de forma no supervisada.

---

### Word embeddings con FastText

Se trabaja con vectores embebidos (word embeddings) utilizando FastText, que representan palabras en espacios vectoriales continuos capturando relaciones semánticas y sintácticas. A diferencia de Word2Vec, FastText trabaja a nivel de subpalabras (n-gramas de caracteres), lo que le permite generar representaciones incluso para palabras fuera del vocabulario de entrenamiento.

Estos embeddings se utilizan como entrada para tareas de clasificación de texto y análisis de sentimientos.

---

### Preprocesamiento de texto

Se abordan técnicas clave de normalización textual:

- **Stemming**: reduce las palabras a su raíz mediante reglas heurísticas. Es rápido pero puede generar raíces que no corresponden a palabras reales.
- **Lematización**: transforma las palabras a su forma canónica o lema considerando su categoría gramatical. Produce resultados más precisos que el stemming.

Ambas técnicas buscan que diferentes variantes de una palabra sean tratadas como un mismo token, mejorando el rendimiento de los modelos al reducir la dispersión del vocabulario.

---

### Análisis de sentimientos

Se implementa clasificación de sentimientos sobre reseñas de Amazon e IMDB, donde el objetivo es determinar si un texto expresa una opinión positiva o negativa. Se combinan técnicas de preprocesamiento, representación vectorial y modelos de clasificación.

---

### Notebooks

- `MNA_NLP_Actividad_semanas_6y7.ipynb` — Actividades prácticas de NLP
- `MNA_NLP_FastText_embeddings.ipynb` — Embeddings con FastText
- `NLP_ejercicios_complementarios.ipynb` — Ejercicios adicionales de procesamiento de texto
- `SENTIMENT_Movies.ipynb` — Análisis de sentimientos en reseñas de películas
- `Stemming_lemmatization.ipynb` — Comparación de stemming y lematización

### Datos

- `amazon5.txt` — Reseñas de Amazon
- `imdb5.txt` — Reseñas de IMDB
- `embedding_dict.pkl` — Diccionario de embeddings precalculados
