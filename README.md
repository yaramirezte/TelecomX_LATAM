# Análisis de Evasión de Clientes (Churn) – Telecom X

## 📌 Descripción del Proyecto
Este proyecto tiene como objetivo analizar la evasión de clientes (*Churn*) en la empresa **Telecom X**, identificando patrones y factores que influyen en la decisión de cancelar el servicio.  
El análisis se centra en datos demográficos, características del servicio y variables de facturación, con el fin de generar insights útiles para diseñar estrategias de retención.

El proyecto incluye:

- Limpieza y tratamiento de datos provenientes de una API en formato JSON.
- Transformación y estandarización de variables.
- Análisis exploratorio con visualizaciones para identificar patrones de evasión.
- Conclusiones y recomendaciones estratégicas basadas en los datos.

---

## 🛠 Tecnologías y Dependencias
El análisis se realizó utilizando **Python 3.12.12** y las siguientes librerías:

- [pandas](https://pandas.pydata.org/) → Manipulación y limpieza de datos
- [numpy](https://numpy.org/) → Cálculos numéricos
- [plotly](https://plotly.com/python/) → Visualizaciones interactivas
- [matplotlib](https://matplotlib.org/) → Visualizaciones básicas (opcional)

Instalación rápida de dependencias:

```bash
pip install pandas numpy plotly matplotlib
```

## 📂 Estructura del Proyecto
```
.
├── TelecomX_LATAM.ipynb        # Notebook con todo el análisis
├── README.md                   # Este archivo
└── data/
    └── TelecomX_Data.json      # Archivo de datos (o enlace a la API)
```

## 🚀 Uso del Proyecto

1. Clonar el repositorio
   ```
   git clone https://github.com/tu_usuario/TelecomX_LATAM.git
   ```
2. Abrir el notebook en Jupyter o Google Colab:
    ```
    jupyter notebook TelecomX_LATAM.ipynb
     ```
3. Ejecutar las celdas paso a paso:
   - Carga y normalización de datos desde la API.
   - Limpieza y transformación de columnas.
   - Creación de variables adicionales como Cargos_Diarios y Segmento_Gasto_Diario.
   - Análisis exploratorio con gráficos de evasión según variables categóricas y numéricas.
   - Conclusiones y recomendaciones estratégicas.
     
## 📊 Resultados Destacados

- Los clientes con menor antigüedad presentan mayor probabilidad de cancelar el servicio.
- Los contratos mes a mes están asociados a mayores tasas de evasión.
- Clientes con menor gasto total acumulado tienden a abandonar el servicio.
- Algunas características del método de pago y tipo de contrato muestran patrones claros de riesgo.
- Estos insights permiten diseñar estrategias de retención temprana, ofertas personalizadas y mejorar la fidelización.

## ⚠ Posibles Problemas o Consideraciones

- Algunos registros iniciales contenían valores nulos o inconsistentes que fueron corregidos.
- Las variables categóricas fueron transformadas a valores binarios para facilitar el análisis.
- Las visualizaciones interactúan mejor en entornos como Google Colab o Jupyter Notebook, pero pueden exportarse a HTML para compartir.

## 👨‍💻 Sobre mí
¡Hola! Soy Yeni Andrea Ramírez, apasionada por los datos y entusiasta del análisis, SQL e ingeniería de datos. Este proyecto fue desarrollado como parte de la especialización en Data Science de Alura Latam, y me permitió aplicar de manera práctica los conocimientos adquiridos en el curso, incluyendo limpieza de datos, análisis exploratorio y visualización de información. Forma parte de mi portafolio para mostrar mis habilidades en soluciones basadas en datos reales.

📫 Conecta conmigo:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yeni-andrea-ramirez-tellez-crm/)

