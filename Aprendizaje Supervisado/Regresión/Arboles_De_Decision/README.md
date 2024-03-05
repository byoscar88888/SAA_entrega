# Arboles de Decisión

## ¿Qué es un Arboles de Decisión?

La regresión con árboles de decisión es una técnica de aprendizaje automático que predice valores numéricos utilizando decisiones binarias basadas en las características de entrada. Cada nodo del árbol representa una característica y una condición de división, con hojas que contienen los valores de salida. Es una herramienta intuitiva y fácil de interpretar, pero puede tender al sobreajuste si no se controla su complejidad. A pesar de ello, es ampliamente utilizada debido a su capacidad para manejar datos no lineales y su interpretación sencilla de los resultados.

## Características Principales:

-Predicción de valores continuos: Los árboles de decisión en regresión dividen el espacio de características y predicen valores numéricos continuos como salida.

-Criterios de división: Utilizan criterios como la reducción de varianza para dividir el espacio de características en cada paso.

-Flexibilidad y interpretabilidad: Son flexibles y capturan relaciones no lineales, además de ser modelos interpretables que pueden visualizarse fácilmente.

-Sensibilidad al sobreajuste: Tienden a sobreajustarse a los datos de entrenamiento, por lo que es importante controlar su crecimiento para evitar problemas de generalización en datos no vistos.

<img src="https://bookdown.org/content/2031/bookdown-demo_files/figure-html/unnamed-chunk-60-1.png" alt="Imagen" width=500>

## Ventajas de un Arboles de Decisión

-Interpretación intuitiva: Los árboles de decisión son fáciles de entender y visualizar, lo que los hace útiles para explicar relaciones en los datos de manera intuitiva.

-Manejo de datos mixtos: Pueden manejar conjuntos de datos con características categóricas y numéricas sin necesidad de preprocesamiento adicional.

-No requieren supuestos sobre la distribución de los datos: A diferencia de algunos modelos paramétricos, los árboles de decisión no asumen una distribución particular de los datos.

## Desventajas de un Arboles de Decisión

-Propensión al sobreajuste: Los árboles de decisión pueden sobreajustarse a los datos de entrenamiento, lo que puede reducir su capacidad de generalización en datos no vistos.

-Sensibilidad a pequeñas variaciones: Son sensibles a pequeñas variaciones en los datos de entrenamiento, lo que puede resultar en diferentes estructuras de árbol para conjuntos de datos ligeramente diferentes.

-Limitaciones en la captura de relaciones complejas: Pueden tener dificultades para capturar relaciones complejas entre características y la variable de salida si estas no pueden ser representadas por límites de decisión simples.

## ¿Cómo funciona el código?

El código comienza importando las bibliotecas necesarias, incluyendo NumPy para operaciones numéricas, Matplotlib para visualización de datos y Scikit-learn (sklearn) para aprendizaje automático, específicamente DecisionTreeRegressor para regresión basada en árboles de decisión y train_test_split para dividir los datos. Luego, se generan datos de ejemplo para la regresión, donde se crea un conjunto de datos de entrada (X) con números aleatorios entre 0 y 5, y un conjunto de datos de salida (y) utilizando la función seno, con ruido añadido para mayor realismo. Posteriormente, se dividen los datos en conjuntos de entrenamiento y prueba, asignando el 20% para prueba y el 80% para entrenamiento. A continuación, se entrena un modelo de regresión basado en árboles de decisión con una profundidad máxima de 2 utilizando los datos de entrenamiento. Finalmente, se visualiza el árbol de decisión entrenado, utilizando Matplotlib para la representación gráfica, coloreando los nodos según la clase mayoritaria en cada uno. En resumen, el código genera datos, entrena un modelo de regresión basado en árboles de decisión y visualiza el árbol resultante, ofreciendo una representación de cómo el modelo divide el espacio de características para realizar predicciones de regresión.
