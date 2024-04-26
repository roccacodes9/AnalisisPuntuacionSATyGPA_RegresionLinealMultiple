Título del Repositorio: Análisis de Regresión Lineal Múltiple y R2R2 Ajustado

Contenido del Repositorio:

    Jupyter Notebook (Archivo Python):
        Contiene el código para realizar un análisis de regresión lineal múltiple utilizando el conjunto de datos proporcionado en el archivo "1.02. Multiple linear regression.csv".
        Importa las bibliotecas relevantes, carga los datos, realiza la regresión lineal múltiple, y muestra un resumen de los resultados, incluido el R2R2 ajustado.

    Archivo CSV:
        "1.02. Multiple linear regression.csv": El conjunto de datos utilizado para el análisis, que contiene las variables SAT, GPA y Rand 1,2,3.

    README.md:
        Proporciona una descripción general del repositorio y cómo utilizar el código proporcionado.

Requisitos de Ejecución del Análisis:

    Python 3.x
    Bibliotecas:
        numpy
        pandas
        matplotlib
        statsmodels
        seaborn

Detalles del Análisis:

    El análisis se realiza utilizando regresión lineal múltiple para predecir el GPA (puntuación promedio ponderada) de los estudiantes utilizando las variables SAT y Rand 1,2,3.
    Se ajusta un modelo de regresión lineal múltiple y se muestra un resumen de los resultados utilizando la biblioteca statsmodels.
    Se evalúa el coeficiente de determinación ajustado (R2R2 ajustado) para entender qué proporción de la variabilidad en el GPA se explica por el modelo de regresión, considerando el número de predictores en el modelo.

Resultado del Análisis:

    El análisis revela que el R2R2 ajustado del modelo de regresión lineal múltiple es aproximadamente 0.392, lo que indica que alrededor del 39.2% de la variabilidad en el GPA se explica por las variables SAT y Rand 1,2,3 incluidas en el modelo.
    Los coeficientes estimados para las variables SAT y Rand 1,2,3 también se muestran en el resumen, junto con sus estadísticas asociadas, como el valor t y el valor p. Estos coeficientes proporcionan información sobre la relación entre las variables predictoras y la variable de respuesta (GPA).
