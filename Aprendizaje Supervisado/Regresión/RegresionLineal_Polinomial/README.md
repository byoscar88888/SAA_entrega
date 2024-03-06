# Regresión Lineal

## ¿Qué es una Regresión Lineal?

La regresión lineal busca modelar la relación entre dos o más variables asumiendo que esta relación es lineal, es decir, se puede representar como una línea recta en un gráfico.
Es útil cuando los datos muestran una tendencia lineal, es decir, cuando los puntos parecen seguir una línea recta cuando se trazan en un gráfico.
Es fácil de interpretar y entender, ya que la relación entre las variables se describe mediante una ecuación lineal.

## Características Principales:

-Modelo Lineal: Establece una relación lineal entre la variable dependiente y las variables independientes.

-Coeficientes de Regresión: Cuantifican la relación entre las variables independientes y la variable dependiente.

-Método de Mínimos Cuadrados: Estima los coeficientes minimizando la suma de los cuadrados de las diferencias entre los valores observados y los predichos.

-Aplicaciones Amplias: Utilizada en diversos campos para modelar relaciones entre variables continuas.

<img src="https://es.mathworks.com/discovery/linear-regression/_jcr_content/mainParsys/band_1231704498_copy/mainParsys/columns_copy_copy/576c621e-2672-40ed-a0dc-e9e61b6f50d2/columns_copy/4a00ee99-d2e4-4625-991c-ded888e86b86/image_copy.adapt.full.medium.jpg/1701682046758.jpg" alt="Imagen" width=500>

## Ventajas de una Regresión Lineal

-Simplicidad: Es un modelo fácil de entender e interpretar, lo que lo hace adecuado para análisis exploratorios y explicativos.

-Eficiencia Computacional: Los algoritmos de regresión lineal son computacionalmente eficientes y pueden manejar grandes conjuntos de datos sin problemas.

-Interpretación Directa: Los coeficientes de regresión tienen una interpretación directa en términos de la relación entre las variables predictoras y la variable de respuesta.

## Desventajas de una Regresión Lineal

-Asunciones Rigurosas: Requiere que se cumplan estrictas suposiciones, como la linealidad, la homocedasticidad y la independencia de los errores, lo que puede ser difícil de garantizar en la práctica.

-Sensibilidad a Valores Atípicos: La presencia de valores atípicos puede sesgar los resultados y afectar la precisión del modelo.

-Limitaciones en la Complejidad del Modelo: No puede capturar relaciones no lineales entre las variables predictoras y la variable de respuesta sin transformaciones adicionales.

## ¿Cómo funciona el código?


Este código en Python utiliza la biblioteca NumPy para la generación de datos sintéticos y la manipulación de matrices, Matplotlib para la visualización de los datos y scikit-learn para construir y entrenar un modelo de regresión lineal. Primero, se generan datos sintéticos para una regresión lineal con ruido. Luego, se crea y se entrena un modelo de regresión lineal utilizando los datos generados. Finalmente, se visualiza el ajuste del modelo de regresión lineal sobre los datos de entrenamiento mediante una dispersión de puntos y la línea de regresión calculada, mostrando así la relación entre la variable independiente (X) y la variable dependiente (y).





