# 📊Procesamiento y Limpieza de Datos con Python

📝 _Resumen_

Este proyecto aborda un proceso completo de Data Wrangling y Análisis Exploratorio de Datos (EDA) sobre el dataset de préstamos de Kiva.

El objetivo principal es limpiar, transformar y analizar los datos para entender la distribución de los microcréditos a nivel global, con especial foco en:

Inclusión financiera
Distribución por género
Sectores económicos

⚙️ _Pipeline de Datos_

El flujo de trabajo implementado en el notebook sigue las siguientes etapas:

1. Carga y Snapshot
Importación del dataset
Creación de una copia de respaldo para preservar los datos originales
2. Limpieza Técnica
Conversión de tipos de datos:
Fechas → datetime
Montos → numeric
Tratamiento de valores nulos
Eliminación de registros duplicados
Normalización de texto:
Conversión a minúsculas
Eliminación de espacios innecesarios
3. Ingeniería de Características (Feature Engineering)
Creación de rangos de préstamo:
Bajo
Medio
Alto
Discretización de variables numéricas
Formateo de moneda para mejorar la visualización
4. Tratamiento de Outliers
Identificación de valores atípicos mediante el método de Rango Intercuartílico (IQR)
Ajuste o eliminación según criterio analítico
5. Visualización de Datos
Gráficos utilizados:
Barras
Histogramas
Diagramas de caja (boxplots)
Análisis visual para detectar patrones y tendencias

🔍 _Hallazgos Principales_

1. Enfoque de Género

Se observa una alta participación de mujeres en los préstamos, lo que refleja el enfoque de inclusión financiera del modelo de microcréditos.

2. Distribución del Capital

La mayoría de los préstamos se concentran en el rango “Bajo”, confirmando la naturaleza de microfinanciación.

3. Distribución Geográfica

Los préstamos se concentran principalmente en:

África
Asia

🛠️ _Tecnologías Utilizadas_

Python 3.12
Pandas → Manipulación y limpieza de datos
Matplotlib & Seaborn → Visualización de datos
Google Colab → Entorno de desarrollo en la nube

🚀 _Posibles Mejoras_

Incorporar análisis temporal (evolución de préstamos en el tiempo)
Crear dashboards interactivos (Power BI / Tableau)
Aplicar modelos predictivos para estimar comportamiento de préstamos
