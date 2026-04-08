## Series de Tiempo

En esta sección se trabaja el análisis de series de tiempo, abordando fundamentos teóricos e implementación práctica en Python para el modelado y predicción de datos temporales.

---

### Introducción a las series de tiempo

Una serie de tiempo es una secuencia de observaciones registradas en distintos momentos, generalmente a intervalos regulares (horarios, diarios, semanales, mensuales, trimestrales o anuales). El objetivo principal es analizar el comportamiento de los datos a lo largo del tiempo para identificar patrones y realizar predicciones.

---

### Análisis y visualización

Se utilizan métodos estadísticos para:

- Identificar tendencias a largo plazo
- Detectar patrones de estacionalidad
- Analizar la variabilidad y los ciclos
- Descomponer la serie en sus componentes (tendencia, estacionalidad, residuo)

Las series se visualizan mediante gráficos de líneas que permiten interpretar la evolución temporal de los datos de forma clara.

---

### Modelos implementados

**Modelos autorregresivos (AR)**: modelan el valor actual como una combinación lineal de valores pasados de la misma serie.

**Promedios móviles (MA)**: modelan el valor actual en función de errores pasados del modelo.

**GARCH (Generalized Autoregressive Conditional Heteroskedasticity)**: captura la volatilidad condicional en series financieras, donde la varianza no es constante sino que depende de la volatilidad pasada. Especialmente útil en mercados financieros donde se observan clusters de volatilidad.

**Prophet**: librería desarrollada por Meta para forecasting automatizado, que maneja tendencias, estacionalidad múltiple y días festivos de forma nativa.

---

### Implementación en Python

Se utiliza `yfinance` para descargar datos financieros reales (S&P 500, acciones individuales), `Statsmodels` para modelos estadísticos clásicos y `Prophet` para predicciones automatizadas. También se cubre el manejo de fechas con `datetime` para la correcta indexación temporal de los datos.

---

### Notebooks

- `Series de tiempo 01.ipynb` — Introducción y conceptos fundamentales
- `Datetime.ipynb` — Manejo de fechas y timestamps en Python
- `Autorregresivo 1.ipynb` — Modelos autorregresivos
- `Moving Average MA.ipynb` — Modelos de promedios móviles
- `GARCH.ipynb` — Modelo GARCH básico
- `Procesos_GARCH.ipynb` — Procesos GARCH avanzados
- `EuStockMarkets.ipynb` — Análisis de mercados bursátiles europeos
- `Prediction_microsoft_Prophet.ipynb` — Predicción con Prophet
- `Statsmodels_&_Prophet.ipynb` — Comparación entre Statsmodels y Prophet

### Datos

- `AirPassengers.csv` — Dataset clásico de pasajeros aéreos
- `dc.csv` — Datos complementarios
- `AR.pdf` / `TS 01.pdf` — Material teórico
