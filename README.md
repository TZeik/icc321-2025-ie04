
-----

# 📊 Visualización de Datos Avanzada con Python (Matplotlib & Seaborn)

## 📘 Informe de Investigación 4

**Materia:** Inteligencia de Negocios

**Tema:** Librerías para Visualización de Datos

**Autores:**

  - Randy Alexander Germosén Ureña *(1013-4707)*
  - Fernando Almonte Delgado *(1015-7628)*

**Repositorio:** [icc321-2025-ie04](https://github.com/TZeik/icc321-2025-ie04) <img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" width="15" height="15"/>

-----

## 🎯 Objetivo del Proyecto

El propósito de este informe es profundizar en el conocimiento y uso de las librerías de gráficos más populares para Python: **matplotlib.pyplot** y **seaborn**

A través de la resolución de cinco problemas prácticos, se busca aplicar conceptos de visualización para analizar patrones en salud, comercio electrónico, bienestar global, química y geografía, justificando la elección de cada gráfico según el público objetivo

-----

## 📂 Datasets Utilizados

Para este informe se utilizaron cinco conjuntos de datos obtenidos de Kaggle:

1.  **Stroke Prediction Dataset:** Riesgos de ACV y hábitos de vida.
2.  **Online Shoppers Purchasing Intention:** Comportamiento de usuarios en e-commerce.
3.  **Global Happiness Scores:** Felicidad, economía y bienestar mundial.
4.  **Wine Quality Dataset:** Propiedades físico-químicas del vino.
5.  **Meteorite Landings:** Registro histórico de caída de meteoritos.

-----

## 🧠 Metodología

**El desarrollo de la investigación se estructuró en las siguientes etapas para cada dataset:**

1.  **Carga y Limpieza:** Se importaron los datos en **Jupyter Notebook** y se realizó el pre-procesamiento necesario, como la conversión de fechas y filtrado de datos (ej. meteoritos post-2000).
2.  **Agrupación y Cálculo:** Se calcularon métricas clave, como la media de glucosa por tipo de trabajo y estatus de fumador, o matrices de correlación para variables químicas.
3.  **Visualización Estratégica:** Se generaron gráficos específicos para cada caso de estudio:
      * **Barplots y Heatmaps** para comparar categorías cruzada.
      * **Boxplots y Violin plots** para analizar distribuciones de intención de compra.
      * **Scatter y Bubble plots** para relacionar riqueza, salud y felicidad.
      * **Correlogramas** para identificar relaciones entre componentes del vino.
      * **Mapas Geográficos** para ubicar impactos de meteoritos.
4.  **Análisis Crítico:** Se documentó en celdas Markdown la interpretación de cada gráfico, discutiendo tendencias, grupos "outliers" y la claridad visual para distintos públicos.

-----

## 📊 Resultados Destacados

El análisis visual permitió extraer conclusiones importantes, tales como:

  * La identificación de grupos de alto riesgo de salud mediante mapas de calor, facilitando la lectura para personal médico.
  * La diferenciación del comportamiento de usuarios que compran vs. los que no, observando la distribución de valores de página (`PageValues`).
  * La correlación positiva entre el desarrollo económico (`Log GDP`) y la felicidad percibida a nivel mundial.
  * La influencia de variables como la acidez y el alcohol en la calidad sensorial del vino.
  * La concentración geográfica de hallazgos de meteoritos en regiones específicas durante las últimas décadas.

-----

## 🧩 Herramientas Utilizadas

  - **Python** (Entorno de Jupyter Notebook)
  - **Librerías principales:**
      - `pandas` – Manipulación y análisis de dataframes.
      - `numpy` – Cálculos numéricos y manejo de matrices.
      - `matplotlib.pyplot` – Creación de gráficos base y personalización.
      - `seaborn` – Visualización estadística avanzada y estética (Heatmaps, Violin plots).
      - `geopandas` – Visualización de datos geoespaciales.

-----
