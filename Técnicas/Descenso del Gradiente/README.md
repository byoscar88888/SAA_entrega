# Descenso del Gradiente

## ¿Qué es el Descenso del Gradiente?

El descenso del gradiente es un algoritmo de optimización que ajusta iterativamente los parámetros de un modelo en la dirección que minimiza una función objetivo. Esto se logra calculando el gradiente de la función objetivo con respecto a los parámetros y actualizando los parámetros en la dirección opuesta al gradiente. Se repite hasta alcanzar un mínimo o después de un número de iteraciones. Es fundamental en el entrenamiento de modelos de aprendizaje automático.

## Características Principales:

-Algoritmo iterativo: Minimiza la función de pérdida ajustando los parámetros del modelo en la dirección opuesta al gradiente.

-Controlado por la tasa de aprendizaje: La tasa de aprendizaje determina el tamaño de los pasos que da el algoritmo en cada iteración.

-Ampliamente utilizado en el aprendizaje automático: Es fundamental en algoritmos como la regresión lineal, la regresión logística y las redes neuronales.

-Puede converger a mínimos locales: Aunque busca minimizar la función de pérdida, puede no encontrar el mínimo global en funciones no convexas.

<img src="https://numerentur.org/wp-content/uploads/2018/08/gradiente-descendente-grafico60a.png" alt="Imagen" width="400">

## Ventajas del Descenso del Gradiente

-Eficiencia en grandes conjuntos de datos: El descenso del gradiente es escalable y eficiente, lo que lo hace adecuado para trabajar con conjuntos de datos grandes y complejos.

-Flexibilidad en la optimización: Puede utilizarse para optimizar una amplia variedad de funciones de pérdida, lo que lo hace versátil en diferentes contextos de aprendizaje automático.

-Adaptabilidad a problemas no lineales: Puede manejar problemas de optimización no lineales y no convexas, lo que lo hace útil en modelos más complejos y profundos.


## Desventajas del Descenso del Gradiente

-Dependencia de la tasa de aprendizaje: La elección incorrecta de la tasa de aprendizaje puede afectar la convergencia del algoritmo.

-Sensibilidad a condiciones iniciales: La estabilidad del descenso del gradiente puede depender de las condiciones iniciales de los parámetros del modelo.

-Requisito de función de pérdida diferenciable: Necesita que la función de pérdida sea diferenciable en todos los puntos, lo que puede limitar su aplicabilidad en algunos casos.

## ¿Cómo funciona el código?

El código utiliza el algoritmo de descenso del gradiente para encontrar el mínimo de una función cuadrática. Primero, se define la función cuadrática y su derivada. Luego, se ejecuta el descenso del gradiente con una tasa de aprendizaje y un número de iteraciones dados. Finalmente, se visualiza el proceso de descenso del gradiente sobre la función cuadrática. Este proceso nos ayuda a entender cómo el algoritmo encuentra el mínimo de la función ajustando iterativamente el parámetro ( x ) con base en la pendiente de la función en cada punto.

<img src="https://turing.iimas.unam.mx/~ivanvladimir/slides/misc/img/parabola.svg" alt="Imagen" width="400">

El código implementa el algoritmo de descenso del gradiente para encontrar un mínimo local en una función polinómica de grado 4. Se define la función y su derivada, se ejecuta el descenso del gradiente con una tasa de aprendizaje y un número de iteraciones dados, y se grafica el proceso de descenso del gradiente sobre la función. El resultado muestra cómo el algoritmo encuentra un mínimo local ajustando iterativamente el parámetro x basándose en la pendiente de la función en cada punto.

<img src="https://cdn.kastatic.org/ka-perseus-graphie/e50876c2fb4d3388fb86413f3d2bd7ec9cfbcd20.svg" alt="Imagen" width="400">



