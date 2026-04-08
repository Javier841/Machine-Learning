## Portfolio Theory

En esta sección se abordan los fundamentos de la teoría de portafolios, combinando conceptos financieros con herramientas cuantitativas para el análisis, optimización y gestión de inversiones.

---

### Análisis de rendimientos y riesgo

Se estudia el comportamiento de los activos financieros a través del análisis de rendimientos históricos. Se calculan métricas de riesgo fundamentales:

- **Value at Risk (VaR)**: cuantifica la pérdida máxima esperada en un periodo dado con un nivel de confianza determinado.
- **Conditional Value at Risk (CVaR)**: mide la pérdida esperada cuando se supera el umbral del VaR, proporcionando una visión más completa del riesgo de cola.

---

### Modelo de Markowitz y frontera eficiente

Se implementa el modelo clásico de Markowitz para la construcción de portafolios eficientes. La frontera eficiente representa el conjunto de portafolios que maximizan el rendimiento esperado para cada nivel de riesgo. Este enfoque permite:

- Comprender el balance entre riesgo y retorno
- Identificar el portafolio de mínima varianza
- Calcular el portafolio de máximo Sharpe ratio
- Visualizar la línea del mercado de capitales (Capital Market Line)

---

### Diversificación y sus límites

Se evalúa hasta qué punto la combinación de activos puede reducir el riesgo total de un portafolio. Se analiza cómo la correlación entre activos determina los beneficios de la diversificación y se identifican los escenarios donde diversificar deja de agregar valor.

---

### CPPI (Constant Proportion Portfolio Insurance)

Se introduce el modelo CPPI como estrategia de protección de capital, donde se asigna dinámicamente entre activos riesgosos y activos seguros en función de un colchón (cushion) sobre un piso de protección. Esto permite participar en las ganancias del mercado mientras se limitan las pérdidas.

---

### Gestión de activos y pasivos

Se aborda el Asset-Liability Management, enfocándose en cómo alinear inversiones con obligaciones futuras. Este aspecto es clave en instituciones financieras y fondos de inversión donde los compromisos futuros deben cubrirse con los rendimientos del portafolio.

---

### Notebooks y módulos

- `EDHEC_Portfolio_Management_Consolidado.ipynb` — Laboratorio completo de gestión de portafolios
- `edhec_risk_kit.py` — Kit de herramientas para análisis de riesgo
- `edhec_risk_kit_oop.py` — Versión orientada a objetos del risk kit

### Datos

Incluye datasets de Fama-French (factores de riesgo diarios y mensuales), índices de hedge funds EDHEC, retornos de BRK-A, portafolios formados por capitalización de mercado e índices industriales (30 y 49 industrias).
