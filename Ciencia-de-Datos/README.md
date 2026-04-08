## Ciencia de Datos

En esta sección se reúnen prácticas y aplicaciones relacionadas con el campo de la ciencia de datos, integrando herramientas de análisis, bases de datos y procesamiento de información sobre datos reales.

---

### Análisis de datos con Pandas

Se utiliza la librería Pandas para el análisis exploratorio de datos, incluyendo:

- Carga de datasets en distintos formatos (`.csv`, `.sqlite`)
- Exploración inicial con métodos como `.head()`, `.describe()`, `.info()`
- Limpieza y transformación de datos
- Filtrado, agrupación y agregación de información
- Preparación de datos para análisis posteriores o modelos predictivos

Se trabaja con el dataset de IMDB, que contiene información sobre películas, permitiendo aplicar técnicas de manipulación sobre datos reales con estructura tabular.

---

### Bases de datos NoSQL con MongoDB

Se introduce MongoDB como base de datos NoSQL, utilizando la librería `pymongo` para:

- Establecer conexión con un clúster de MongoDB Atlas
- Validar la conexión mediante comandos como `ping`
- Realizar operaciones CRUD (crear, leer, actualizar, eliminar)
- Ejecutar consultas y agregaciones sobre colecciones de documentos

Este enfoque permite trabajar con datos no estructurados y esquemas flexibles, complementando las bases de datos relacionales tradicionales.

---

### Análisis de sentimientos

Se aplican técnicas de procesamiento de texto y clasificación para analizar el sentimiento en reseñas de películas, combinando preprocesamiento de texto con modelos de clasificación para determinar si una reseña es positiva o negativa.

---

### Notebooks

- `PANDAS.ipynb` — Análisis y exploración de datos con Pandas
- `MongoDB.ipynb` — Introducción y conexión a MongoDB
- `PyMongo.ipynb` — Operaciones con PyMongo
- `SENTIMENT_Pelis.ipynb` — Análisis de sentimientos en reseñas de películas

### Datos

- `IMDB-Movie-Data.csv` — Dataset tabular de películas
- `IMDB.sqlite` — Base de datos SQLite con información de IMDB
