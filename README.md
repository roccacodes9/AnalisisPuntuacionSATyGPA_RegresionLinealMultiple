Análisis de Regresión Lineal Múltiple

Este repositorio contiene un análisis detallado de regresión lineal múltiple realizado en Python utilizando bibliotecas como NumPy, Pandas, Matplotlib, Statsmodels y Seaborn. El análisis se centra en la relación entre las puntuaciones SAT, las variables aleatorias (Rand 1,2,3) y los promedios universitarios de calificaciones (GPA).
Contenido del Repositorio

El repositorio contiene los siguientes archivos:

    1.02. Multiple linear regression.csv: Este archivo CSV contiene los datos utilizados en el análisis. Contiene tres columnas: SAT (puntuaciones SAT), Rand 1,2,3 (variables aleatorias) y GPA (promedios universitarios de calificaciones).

    multiple_regression_analysis.ipynb: Este es el cuaderno de Jupyter utilizado para realizar el análisis. Contiene el código Python junto con explicaciones detalladas y visualizaciones del proceso de regresión lineal múltiple.

Requisitos

Para ejecutar el código en el cuaderno de Jupyter, se requieren las siguientes bibliotecas de Python:

    NumPy
    Pandas
    Matplotlib
    Statsmodels
    Seaborn

Se puede instalar estas bibliotecas mediante el gestor de paquetes pip. Por ejemplo:

pip install numpy pandas matplotlib statsmodels seaborn

Ejecución del Análisis

Para ejecutar el análisis, simplemente abre el cuaderno de Jupyter multiple_regression_analysis.ipynb en tu entorno de Jupyter Notebook y ejecuta las celdas secuencialmente. Asegúrate de tener el archivo CSV 1.02. Multiple linear regression.csv en el mismo directorio que el cuaderno.
Detalles del Análisis

El análisis sigue los siguientes pasos:

    Importación de bibliotecas y lectura de datos desde el archivo CSV.
    Verificación de los datos y estadísticas descriptivas.
    Definición de la variable dependiente (GPA) y las variables independientes (SAT y Rand 1,2,3).
    Ajuste de un modelo de regresión lineal múltiple utilizando statsmodels.
    Resumen detallado de los resultados del análisis.

Resultados

El análisis proporciona información sobre la relación entre las puntuaciones SAT, las variables aleatorias y los promedios universitarios de calificaciones. Proporciona coeficientes de regresión que pueden utilizarse para predecir el GPA en función de las puntuaciones SAT y las variables aleatorias.
