# Tripleten-Data-Analyst-project-7
Este repositorio contiene un análisis completo de los datos de uso de la empresa de telecomunicaciones "ConectaTel" para México y Colombia de los años 2022, 2023, 2024 y 2026. 

Datasets en uso: "users_latam.csv" | "plans.csv" |"usage.csv"
Librerias importadas: pandas, numpy, seaborn, matplotlib
Notebook usado: Jupyter Notebook
Lenguaje usado: Python

El archivo "S7 Version-Estudiante-Project-ConnectaTel.ipynb" contiene el Notebook completo dividido en las siguientes secciones separadas por los pasos que se tomaron en el análisis
- Carga y primera revisión de archivos e importación de librerías
- Exploración de los datasets para identificar tipos de datos, nombres de columnas y variables
- Identificación de valores faltantes
- Identificación de valores nulos
- Detección de valores inválidos y sentinels
- Estandarización de formatos y revisión de valores únicos
- Corrección de sentinels y remoción de rangos inconclusos como el año 2026
- Tratamiento de valores nulos
- Agrupación de usuarios por comportamiento de uso
- Creación del dataset combinado "User_profile" con columnas agregadas del dataset agrupado
- Resumen estadístico de uso por usuario en el año 2024
- Visualización de distribuciones por uso y edad mediante histogramas e insights
- Identificación de outliers mediante Boxplots
- Cálculo de límites con metodología IQR
- Generación de insights y recomendaciones para el manejo de los outliers
- Segmentación de clientes por uso y edad, análisis porcentual de los segmentos
- Visualización gráfica de los segmentos por medio de gráficos de barras
- Insight ejecutivo con desglose de métricas y recomendaciones para Stakeholders

Para abrir y ejecutar el Notebook:
- Descarga el archivo "S7 Version-Estudiante-Project-ConnectaTel.ipynb" 
- Dirígete a https://colab.research.google.com
- Una vez en Google Colab, clickea el botón de "Subir notebook" y selecciona el archivo que descargaste
- El notebook debería abrir y ejecutarse automáticamente, en caso de no ejecutarse, clickea el botón "Ejecutar todo" en la parte de arriba del notebook

Guía de reproducción:
- Vas a encontrar celdas de explicación y resúmen, estas solo contienen texto e íconos, no tienen bordes definidos
- Hay celdas de código en Python, las puedes distinguir por su borde definido, un par de corchetes "[]" a la izquierda de la celda, y una breve explicación del código en letras verdes identificada por un numeral "#"
- Vas a encontrar menús desplegables con las tablas y gráficos resultantes de las celdas de código, puedes abrirlas o colapsarlas usando el símbolo "V" o ">" a la izquierda de la celda
- El documento contiene todos los pasos anteriormente descritos, en órden y con numeración, siendo el resumen ejecutivo el Paso 7
