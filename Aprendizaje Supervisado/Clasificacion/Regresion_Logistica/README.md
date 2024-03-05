# Regresión Logística

## ¿Qué es la Regresión Logística?

La regresión logística es un algoritmo de aprendizaje supervisado utilizado para problemas de clasificación binaria. Aunque su nombre incluye "regresión", se usa para clasificar, no para predecir valores continuos. Funciona modelando la relación entre las características de entrada y la probabilidad de que una observación pertenezca a una de dos clases.

Utiliza una función sigmoide para transformar la salida en un valor entre 0 y 1, que se interpreta como la probabilidad de pertenecer a una clase. Luego, se asigna una etiqueta de clase basada en un umbral (generalmente 0.5).

Es un algoritmo simple pero efectivo y se utiliza en una amplia gama de aplicaciones, como detección de spam, diagnóstico médico y análisis de riesgos financieros.

## Características Principales:

-Modelo de Probabilidad Binaria: Predice la probabilidad de que una variable binaria sea 1.

-Función Logística: Transforma la combinación lineal de variables independientes en una probabilidad entre 0 y 1.

-Coeficientes Logarítmicos: Representan el cambio logarítmico en las probabilidades de éxito asociadas con cambios en las variables independientes.

-Evaluación del Modelo: Se realiza mediante métricas como AIC, BIC y el área bajo la curva ROC. Es ampliamente utilizado para clasificación binaria en diversos campos.

<img src="https://datascientest.com/es/wp-content/uploads/sites/7/2020/11/illu_regression_blog-16-1024x562.png" alt="Imagen" width=500>

## Ventajas de la Regresión Logística

-Flexibilidad en la Forma Funcional: A diferencia de otros métodos, como la regresión lineal, no asume una relación lineal entre las variables independientes y la variable dependiente, lo que permite modelar relaciones más complejas.

-Interpretación Intuitiva: Los coeficientes de la regresión logística se pueden interpretar como el cambio en las probabilidades de éxito asociado con un cambio unitario en la variable independiente.

-Buena para Datos Categóricos y Binarios: Es especialmente útil cuando las variables son categóricas o binarias.

## Desventajas de la Regresión Logística

-Sensibilidad a la Selección de Variables: La regresión logística puede ser sensible a la inclusión o exclusión de variables, y la selección de variables incorrectas puede llevar a resultados inexactos.

-Dependencia de la Linealidad en los Logitos: Aunque la regresión logística no asume linealidad entre las variables y la variable dependiente, sí asume linealidad en la escala de logitos. Si esta suposición no se cumple, el modelo puede ser inadecuado.

-No Adecuada para Datos Continuos y Multiclase: Aunque puede manejar variables continuas, está optimizada para variables categóricas y binarias. Además, no es ideal para problemas de clasificación con más de dos clases.

## ¿Cómo funciona el código?


Este código en Google Colab utiliza la biblioteca NumPy para la manipulación de matrices y arreglos, Matplotlib para la visualización de datos y scikit-learn para implementar un modelo de regresión logística. Se importan las bibliotecas necesarias, se definen datos de ejemplo X y y, se crea y entrena un modelo de regresión logística utilizando los datos de entrenamiento, se grafican los puntos de datos y se generan puntos para predecir las probabilidades de clase y trazar la línea de predicción. Luego, se hacen predicciones para una nueva muestra y se grafican, se etiquetan los ejes y se agrega un título a la gráfica. Finalmente, se muestra la leyenda y la gráfica, junto con la predicción para la nueva muestra. En resumen, el código crea un modelo de regresión logística para clasificar puntos de datos en dos clases y visualiza tanto los datos de entrenamiento como las predicciones.


