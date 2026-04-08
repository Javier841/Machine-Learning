## SQL

En esta sección se trabaja con SQL (Structured Query Language), el lenguaje estándar para gestionar y manipular datos en sistemas de bases de datos relacionales.

---

### Bases de datos relacionales

Una base de datos relacional organiza la información en tablas relacionadas entre sí, donde cada fila representa un registro único y cada columna define un tipo de dato específico. Las relaciones entre tablas se establecen mediante claves primarias y foráneas, permitiendo realizar consultas complejas que combinan información de múltiples fuentes.

---

### Sistemas de gestión (DBMS)

Aunque existen múltiples sistemas de gestión de bases de datos (MySQL, PostgreSQL, SQLite, Oracle, IBM Db2), todos utilizan SQL como lenguaje estándar. En esta sección se trabaja con **SQLite**, que permite ejecutar consultas directamente desde Python sin necesidad de un servidor externo, lo cual lo hace ideal para prototipado y análisis de datos.

---

### SQL aplicado a ciencia de datos

SQL es una herramienta fundamental en el flujo de trabajo de un data scientist, permitiendo:

- Consultar y filtrar grandes volúmenes de datos
- Realizar agregaciones (SUM, AVG, COUNT, MAX, MIN)
- Combinar tablas mediante JOINs (INNER, LEFT, RIGHT, FULL)
- Crear subconsultas y vistas
- Preparar datos para análisis o modelos de machine learning

---

### Integración con Python

Se utiliza la librería `sqlite3` para conectar Python con bases de datos SQLite, permitiendo ejecutar consultas SQL directamente desde notebooks de Jupyter y cargar los resultados en DataFrames de Pandas para su posterior manipulación y análisis.

---

### Notebooks

- `SQL.ipynb` — Fundamentos de SQL: SELECT, WHERE, ORDER BY, GROUP BY
- `SQL 2-2.ipynb` — Consultas avanzadas, JOINs y subconsultas
- `Sqlite_IMDB.ipynb` — Análisis de datos de IMDB con SQLite

### Datos

- `movie.sqlite` — Base de datos de películas
- `SQL 2 - Clients.pdf` — Ejercicios con datos de clientes
