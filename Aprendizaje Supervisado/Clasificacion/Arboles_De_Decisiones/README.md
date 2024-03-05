# Título Grande

## ¿Qué es un árbol de decisión?

Un árbol de decisión es una representación gráfica de un proceso de toma de decisiones, donde cada nodo representa una decisión y las ramas representan las opciones disponibles en cada etapa del proceso. Es una herramienta útil para visualizar y comprender los pasos lógicos involucrados en la toma de decisiones en diferentes situaciones.

## Características Principales:

-Fácil de entender: Los árboles de decisión son modelos intuitivos y fáciles de entender. Puedes visualizar el árbol de decisión para comprender cómo se toman las decisiones y qué características son más importantes.

-Versatilidad: Los árboles de decisión pueden manejar tanto datos numéricos como categóricos. 

-No requiere normalización de datos: A diferencia de algunos otros modelos, como las redes neuronales, los árboles de decisión no requieren que los datos estén normalizados.

-Versatilidad: Los árboles de decisión pueden manejar tanto datos numéricos como categóricos. Esto los hace útiles para una amplia gama de problemas de clasificación.

<img src="https://miro.medium.com/v2/resize:fit:1400/1*pxHwmJyAmH7iCxNmTVaf2Q.png" alt="Imagen" width="400">

## Ventajas de los árboles de decisión

-Interpretación fácil: Los árboles de decisión son fáciles de interpretar y explicar, lo que los hace útiles tanto para expertos como para no expertos en el campo.

-Requiere menos preprocesamiento de datos: A menudo, los datos pueden usarse sin necesidad de preprocesamiento, como la normalización o la eliminación de valores atípicos.

## Desventajas de los árboles de decisión

-Inestables: Pequeñas variaciones en los datos de entrada pueden resultar en cambios significativos en la estructura del árbol, lo que los hace inestables.

-No adecuados para ciertos tipos de relaciones complejas: Pueden tener dificultades para modelar relaciones complejas como las que se encuentran en problemas de regresión no lineal.

## ¿Cómo funciona el código?


El código comienza importando las bibliotecas necesarias y cargando el conjunto de datos Iris, que contiene mediciones de diferentes características de flores de iris. Luego, divide los datos en conjuntos de entrenamiento y prueba para evaluar el rendimiento del modelo. Se utiliza un algoritmo de árbol de decisión para construir el modelo, que se entrena con los datos de entrenamiento y se evalúa con los datos de prueba. Se calcula la precisión del modelo y se imprime un informe de clasificación detallado que muestra métricas como precisión, recall y F1-score para cada clase. Finalmente, se utiliza la biblioteca graphviz para visualizar el árbol de decisión generado por el modelo, lo que proporciona una comprensión intuitiva de cómo se toman las decisiones de clasificación. Este proceso ayuda a entender mejor cómo funciona el modelo y cómo se clasifican las diferentes clases de flores de iris en función de sus características.
