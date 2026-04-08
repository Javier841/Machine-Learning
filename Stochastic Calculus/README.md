## Cálculo Estocástico

En esta sección se presenta una ruta de aprendizaje para el estudio del cálculo estocástico, integrando teoría de probabilidad avanzada, procesos estocásticos y herramientas matemáticas. El contenido se basa en diversos materiales incluyendo libros y notas especializadas.

---

### Fundamentos de probabilidad avanzada

Se parte de los conceptos esenciales que permiten construir una base sólida:

- Espacios de probabilidad (Ω, F, P)
- Completitud de un espacio de probabilidad
- Conjuntos nulos y su papel en la teoría de la medida

Un espacio de probabilidad es completo si todo subconjunto de un conjunto de probabilidad cero también es medible. Esta propiedad evita inconsistencias en construcciones probabilísticas más avanzadas.

---

### Variables aleatorias y tiempos de espera

Se estudian variables aleatorias continuas con énfasis en la distribución exponencial y sus propiedades. Si T₁, ..., Tₙ son variables exponenciales independientes, entonces el mínimo de todas ellas representa el primer evento que ocurre en un sistema de múltiples procesos aleatorios, lo cual es fundamental para modelar sistemas de colas y procesos de Markov.

---

### Cadenas de Markov en tiempo continuo

Se introducen procesos estocásticos en tiempo continuo, cubriendo:

- Definición y propiedades de cadenas de Markov en tiempo continuo
- Tiempos medios de paso y clasificación de estados
- Procesos de nacimiento y muerte
- Procesos de nacimiento puro
- Ecuaciones forward y backward de Kolmogorov

Estas ecuaciones describen cómo evoluciona la distribución de probabilidad del proceso a lo largo del tiempo.

---

### Movimiento Browniano y procesos gaussianos

Se estudia el movimiento Browniano como proceso fundamental del cálculo estocástico, caracterizado por incrementos independientes y estacionarios con distribución normal. Si Bₜ es un movimiento Browniano, entonces Bₜ - Bₛ tiene distribución N(0, t-s).

Se analizan momentos de orden superior y propiedades de procesos gaussianos que generalizan el movimiento Browniano.

---

### Martingalas

Se introduce el concepto de martingala, interpretada intuitivamente como un "juego justo" donde el valor esperado futuro, dado el presente, es igual al valor actual. Las martingalas son fundamentales en finanzas cuantitativas, teoría de apuestas y modelado estocástico moderno.

---

### Integración estocástica

Se construye la integral estocástica de forma rigurosa:

1. Se define inicialmente para procesos simples (funciones escalonadas)
2. Se extiende mediante límite en media cuadrática (L²)
3. Se motiva la necesidad de superar las limitaciones de las definiciones clásicas de integral

Este enfoque permite definir integrales respecto al movimiento Browniano, que constituyen la base del cálculo estocástico y son esenciales para la valoración de derivados financieros.

---

### Material

Incluye notas teóricas, sets de problemas resueltos y material sobre movimiento Browniano, martingalas, cadenas de Markov en tiempo continuo, vectores gaussianos, la fórmula de Itô y el teorema de existencia de Daniell-Kolmogorov.
