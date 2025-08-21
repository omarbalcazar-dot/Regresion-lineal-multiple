# Regresion-lineal-multiple

El objetivo de esta actividad es aplicar los conceptos de regresión lineal múltiple a un conjunto de datos reales, provenientes de la NASA.

El dataset utilizado fue NASA.csv, contiene seis variables, de las cuales cinco corresponden a medidas de entrada y una representa la salida a predecir. Las variables son:

• Frecuencia

• Ángulo

• Longitud

• Velocidad

• Espesor

• Presión

La actividad consiste en desarrollar los siguientes pasos:

1. Importación y exploración de datos: cargar el archivo CSV, revisar dimensiones y mostrar una muestra inicial de observaciones.
2. División de datos: separar el dataset en entranamiento (70%) y prueba (30%) de manera aleatoria, verificando las dimensiones de cada subconjunto
3. Entrenamiento del modelo: ajustar un modelo de regresión lineal múltiple utilizando las cinco variables predictoras para estimar la presion. Se debe mostrar un resumen del modelo con los coeficientes, errores estándar, valores t y p-values
4. Análisis de significancia: interpretar los resultados para identificar si existe al menos una variable significativa en el modelo, cuáles variables muestran asociación lineal con la salida y cuál se considera la más importante
5. Evaluación del desempeño: calcular el RSE y el coeficiente de determinación R² tanto en el entrenamiento como en el de validación
6. Visualización de resultados: generar una gráfica de dispersión que compare valores reales vs valores estimados de la presión en los datos de validación, incluyendo la línea de referencia ideal.

La actividad va de 3 documentos:

[reporte html]()

[reporte ipynb]()

[reporte NASA.cvs]()
