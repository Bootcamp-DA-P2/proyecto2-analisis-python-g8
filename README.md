# proyecto2-analisis-python-g8
_Procesamiento y limpieza de datos con Python_

Resumen
Este proyecto realiza un proceso completo de Data Wrangling y Análisis Exploratorio de Datos (EDA) sobre el conjunto de datos de préstamos de Kiva. El objetivo es limpiar, transformar y visualizar los datos para entender cómo se distribuyen los microcréditos a nivel global, con un enfoque especial en la inclusión financiera por género y sectores económicos.

Pipeline de Datos
El flujo de trabajo aplicado en este notebook sigue los siguientes pasos:

Carga y Snapshot: Importación de datos y respaldo del dataset original.

- Limpieza Técnica: * Conversión de tipos (fechas a datetime, montos a numeric).

- Tratamiento de valores nulos y eliminación de duplicados.

- Normalización de textos (países y sectores en minúsculas y sin espacios).

- Ingeniería de Características (Feature Engineering):

- Creación de Rangos de Préstamo (Bajo, Medio, Alto) mediante discretización.

- Formateo de moneda para visualización.

- Tratamiento de Outliers: Identificación y gestión de valores atípicos mediante el método de Rango Intercuartílico (IQR).

- Visualización: Creación de gráficos de barras, histogramas y diagramas de caja para interpretar tendencias.
- 

_Hallazgos Principales_
1.- Enfoque de Género: Se observa una presencia dominante de mujeres en el dataset, alineado con la misión de empoderamiento de Kiva.

2.- Distribución de Capital: La mayoría de los préstamos se concentran en el rango "Bajo", lo que confirma la naturaleza de "microcrédito" de la plataforma.

Países Clave: La mayoría de los préstamos se concentran en África y Ásia. 

_Tecnologías Utilizadas_

Python 3.12

Pandas: Manipulación y limpieza de datos.

Seaborn & Matplotlib: Visualización estática de datos.

Google Colab: Entorno de ejecución en la nube.
