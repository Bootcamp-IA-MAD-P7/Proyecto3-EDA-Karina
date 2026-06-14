# Análisis Exploratorio de Datos (EDA): Pacientes con Cáncer en India (2022-2025)

Este proyecto consiste en un **Análisis Exploratorio de Datos (EDA)** exhaustivo aplicado a un conjunto de datos de 100,000 registros de pacientes diagnosticados con cáncer en la India entre los años 2022 y 2025. El objetivo principal es identificar patrones demográficos, evaluar la severidad clínica en el momento del diagnóstico, analizar la equidad en la asignación de tratamientos y estudiar los factores temporales que impactan en la supervivencia y mortalidad.

---

## 📊 ¿Para qué sirve este EDA?

El Análisis Exploratorio de Datos es la fase más crítica en cualquier proyecto de Ciencia de Datos y Salud Pública. Sirve para:
1. **Validar la Calidad de los Datos:** Detectar anomalías, valores faltantes (nulos) o registros duplicados que puedan distorsionar las conclusiones médicas.
2. **Descubrir Estructuras Ocultas:** Entender la distribución real de variables críticas como la edad, el género y la prevalencia geográfica.
3. **Extraer Insights Clínicos:** Cruzar variables (análisis bivariante) para entender la relación entre la etapa del cáncer, las decisiones de tratamiento y el desenlace final del paciente.
4. **Auditar el Dataset:** Identificar si los datos siguen patrones biológicos reales o si presentan homogeneidades matemáticas que delaten una naturaleza sintética (auditoría de datos).

---

## 🛠️ Tecnologías y Dependencias Usadas

El proyecto está desarrollado íntegramente en **Python** dentro de un entorno virtual controlado (`venv`), utilizando las siguientes librerías especializadas:

* **Manipulación y Limpieza de Datos:** `pandas` y `numpy`
* **Visualización Estadística Avanzada:** `matplotlib.pyplot` y `seaborn`
* **Entorno de Desarrollo:** `Jupyter Notebook` integrado en Visual Studio Code

Las dependencias exactas y sus versiones se encuentran documentadas en el archivo `requirements.txt`.

---

## 📁 Estructura del Proyecto

```text
Proyecto3-EDA-Karina/
│
├── data/
│   └── archive/
│       └── india_cancer_patients_2022_2025.csv  # Dataset principal (100k filas)
│
├── EDA/
│   └── EDA.ipynb                                # Notebook con el código y gráficos
│
├── venv/                                        # Entorno virtual de Python (Ignorado en Git)
├── .gitignore                                   # Filtro protector de Git (Excluye venv y datos pesados)
└── README.md                                    # Documentación del proyecto (Este archivo)
```

