Análisis de Regresión Lineal Múltiple

Este repositorio contiene un script de Python para realizar un análisis de regresión lineal múltiple utilizando el módulo statsmodels y pandas. El análisis se realiza sobre un conjunto de datos que incluye puntuaciones SAT y otras variables predictoras para predecir el GPA de los estudiantes universitarios.
Archivos

    multiple_linear_regression.py: Este script de Python carga los datos desde un archivo CSV, realiza un análisis de regresión lineal múltiple y muestra un resumen de los resultados.

    1.02. Multiple linear regression.csv: El archivo CSV que contiene los datos necesarios para el análisis. Incluye columnas para las puntuaciones SAT, el GPA y otras variables predictoras.

Dependencias

El script requiere las siguientes bibliotecas de Python:

    numpy: Para operaciones numéricas.
    pandas: Para la manipulación y análisis de datos.
    matplotlib: Para visualización de datos.
    statsmodels: Para realizar el análisis de regresión lineal.
    seaborn: Para mejorar la visualización de los resultados.

Para instalar las dependencias, puedes utilizar el siguiente comando:

bash

pip install numpy pandas matplotlib statsmodels seaborn

Uso

    Clona este repositorio o descarga los archivos multiple_linear_regression.py y 1.02. Multiple linear regression.csv en tu sistema local.

    Abre una terminal o línea de comandos y navega hasta el directorio donde guardaste los archivos.

    Ejecuta el script multiple_linear_regression.py usando Python:

    bash

    python multiple_linear_regression.py

    El script cargará los datos, realizará el análisis de regresión lineal múltiple y mostrará un resumen de los resultados en la terminal.

Detalles Técnicos

El script sigue los siguientes pasos para realizar el análisis de regresión lineal múltiple:

    Carga los datos desde el archivo CSV utilizando pandas.
    Preprocesa los datos si es necesario, como la eliminación de valores nulos o la codificación de variables categóricas.
    Define las variables dependientes e independientes.
    Agrega una constante a las variables independientes para incluir el término de intercepción en el modelo de regresión.
    Ajusta el modelo de regresión lineal utilizando el método de Mínimos Cuadrados Ordinarios (OLS) de statsmodels.
    Muestra un resumen de los resultados, que incluye coeficientes de regresión, errores estándar, valores p, R2R2 y Rajustado2Rajustado2​.
