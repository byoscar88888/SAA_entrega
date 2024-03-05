# One Hot Encoding

## ¿Qué es OHE?

-One-Hot Encoding: Es una técnica que convierte variables categóricas en una representación binaria, donde cada valor único se convierte en una nueva columna. Cada fila tiene un valor de 1 en la columna correspondiente al valor de la variable categórica y 0 en las demás columnas.

-Dummy Variables: Similar al One-Hot Encoding, pero en lugar de crear una columna para cada valor único, crea k-1 columnas, donde k es el número de valores únicos de la variable categórica. Esto se hace para evitar la multicolinealidad en modelos lineales, ya que la columna restante se puede deducir a partir de las otras k-1 columnas.

## Características Principales:

-Convertir categóricas a numéricas: Ambas técnicas convierten variables categóricas en formato numérico, facilitando su uso en algoritmos de aprendizaje automático.

-Simplificar manejo de variables categóricas: Permiten incluir variables categóricas en modelos de aprendizaje automático sin necesidad de preprocesamiento adicional.

-Evitar ambigüedad: Al convertir variables categóricas en representaciones numéricas, se evita la ambigüedad en la interpretación de los algoritmos.

-Prevenir multicolinealidad: Las Dummy Variables, en particular, evitan la multicolinealidad en modelos lineales, mejorando la estabilidad y la interpretación del modelo.

<img src="https://miro.medium.com/v2/resize:fit:1358/1*ggtP4a5YaRx6l09KQaYOnw.png" alt="Imagen">

## Ventajas del OHE

-Compatibilidad con algoritmos: Tanto el One-Hot Encoding como las Dummy Variables permiten utilizar variables categóricas en algoritmos de aprendizaje automático que requieren entradas numéricas, como modelos de regresión y clasificación.

-Evita ambigüedad: Convertir variables categóricas en representaciones numéricas evita la ambigüedad en la interpretación de los algoritmos, lo que mejora la precisión y la estabilidad del modelo.

-Facilita el manejo de datos: Simplifica el manejo de variables categóricas en conjuntos de datos, lo que facilita su inclusión en modelos de aprendizaje automático sin necesidad de preprocesamiento adicional.

## Desventajas del OHE

-Expansión del espacio de características: Pueden aumentar la dimensionalidad del conjunto de datos, lo que incrementa el tiempo de entrenamiento y la complejidad del modelo.

-Posible pérdida de información: Al convertir variables categóricas en representaciones numéricas, se puede perder información sobre la relación entre las categorías.

-Mayor consumo de recursos: El uso de estas técnicas puede aumentar el uso de memoria y recursos computacionales, especialmente en conjuntos de datos grandes.

## ¿Cómo funciona el código?


Este código en Python representa un flujo de trabajo típico en un proyecto de aprendizaje automático. Comienza montando Google Drive en Colab para acceder a los datos almacenados, luego importa las bibliotecas necesarias y carga un conjunto de datos desde un archivo CSV. Después de preprocesar los datos, eliminando columnas irrelevantes y convirtiendo variables categóricas en variables dummy, se dividen los datos en conjuntos de entrenamiento y prueba. Se entrena un modelo de regresión lineal utilizando los datos de entrenamiento y se evalúa su rendimiento en ambos conjuntos. Además, se visualiza la relación entre las características y la variable objetivo mediante un gráfico de dispersión. Finalmente, se realiza una división adicional de los datos para entrenar y evaluar otro modelo de regresión lineal, con el objetivo de comparar y mejorar los resultados obtenidos. En resumen, este código proporciona un enfoque completo para el desarrollo y evaluación de modelos de regresión lineal en Python, utilizando técnicas estándar de preprocesamiento de datos y evaluación de modelos.





