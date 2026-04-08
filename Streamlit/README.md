## Streamlit

En esta sección se desarrollan aplicaciones interactivas con Streamlit, orientadas a la visualización y simulación de modelos matemáticos y estadísticos. El objetivo es transformar conceptos teóricos en herramientas dinámicas que permitan explorar datos y procesos en tiempo real.

---

### Cadenas de Markov

Se implementa un dashboard basado en programación orientada a objetos para el análisis de una cadena de Markov de dos estados (V/C). Las visualizaciones interactivas se construyen con Altair, permitiendo representar la evolución de los estados y sus probabilidades de transición de forma clara y dinámica.

---

### Procesos de Poisson

Se incluyen aplicaciones que simulan procesos de Poisson homogéneos (PPH) y no homogéneos (PPNH). Estos modelos permiten simular fenómenos donde los eventos ocurren de forma aleatoria en el tiempo:

- Con tasa constante (PPH): útil para modelar llegadas uniformes a un sistema
- Con tasa variable (PPNH): captura patrones donde la intensidad del proceso cambia con el tiempo

Ejemplos de aplicación incluyen conteo de eventos físicos, tráfico web, llegadas a sistemas de servicio y fenómenos naturales.

---

### Análisis financiero

Se integra la construcción y comparación de portafolios bajo el enfoque de Markowitz, incluyendo variantes con matrices de covarianza ajustadas mediante técnicas de limpieza basadas en Random Matrix Theory (RIE). Se exploran comparaciones entre resultados in-sample y out-of-sample utilizando múltiples activos financieros, permitiendo evaluar la robustez de las estrategias de inversión.

---

### Aplicaciones

- `Markov.py` — Dashboard interactivo de cadenas de Markov
- `poisson.py` — Simulación de procesos de Poisson
- `cafe.py` — Aplicación interactiva de análisis
- `descriptiva.py` — Estadística descriptiva interactiva
- `calendario.py` — Herramienta de calendario
- `clean.py` — Limpieza de datos interactiva
- `jenny.py` — Aplicación complementaria
- `requirements.txt` — Dependencias del proyecto
