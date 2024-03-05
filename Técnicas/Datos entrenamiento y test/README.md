# Título Grande

## ¿Qué son Datos de entrenamiento y test?

"Datos de entrenamiento y test" se refiere a la división de un conjunto de datos en dos partes: un conjunto de datos de entrenamiento y un conjunto de datos de prueba. Esta división es comúnmente utilizada en el aprendizaje automático y la minería de datos para evaluar el rendimiento de un modelo.

Datos de entrenamiento: Estos datos se utilizan para entrenar el modelo. Durante el proceso de entrenamiento, el modelo ajusta sus parámetros utilizando estos datos para aprender patrones y relaciones entre las características de entrada y las etiquetas de salida.

Datos de prueba: Estos datos se utilizan para evaluar el rendimiento del modelo después de que ha sido entrenado. El modelo no ha visto estos datos durante el entrenamiento y se utilizan para evaluar su capacidad para generalizar a nuevos datos. Al proporcionar un conjunto de datos de prueba separado, podemos obtener una estimación más precisa del rendimiento del modelo en datos no vistos.

En resumen, dividir el conjunto de datos en datos de entrenamiento y datos de prueba nos permite entrenar un modelo en un conjunto de datos y evaluar su rendimiento en otro conjunto de datos independiente. Esto nos ayuda a estimar cómo se comportará el modelo en datos nuevos y no vistos.

## Características Principales:

-Evaluación del rendimiento: Permite medir cómo se desempeña el modelo en datos no vistos, ayudando a estimar su capacidad para generalizar.

-Prevención del sobreajuste: Reduce el riesgo de que el modelo memorice los datos de entrenamiento al utilizar datos de prueba independientes.

-Ajuste de parámetros: Los datos de entrenamiento se utilizan para ajustar los parámetros del modelo, permitiéndole aprender patrones y relaciones entre las características de entrada y salida.

-Validación de resultados: Evaluar el modelo en datos de prueba independientes valida su rendimiento, confirmando su eficacia en la generalización a nuevos datos.

<img src="https://qph.cf2.quoracdn.net/main-qimg-b6364f918f4df0c1e3d5370bab4de11e" alt="Imagen" width="400">

## Ventajas de los datos de entrenamiento y test

-Evaluación objetiva del modelo: Permite una evaluación objetiva del rendimiento del modelo en datos no vistos, lo que ayuda a estimar su capacidad para generalizar.

-Prevención del sobreajuste: Reduce el riesgo de sobreajuste al proporcionar datos independientes para la validación del modelo.

-Optimización de parámetros: Facilita la optimización de los parámetros del modelo al permitir ajustes basados en los resultados de la evaluación en datos de prueba.

## Desventajas de los datos de entrenamiento y test

-Posible pérdida de datos: La división de datos puede resultar en una pérdida de datos, especialmente en conjuntos de datos pequeños.

-Sesgo de muestreo: La división aleatoria de datos puede introducir sesgos de muestreo si la distribución de las clases no está equilibrada entre los conjuntos de entrenamiento y prueba.

-No refleja la variabilidad de datos reales: Los datos de prueba pueden no capturar completamente la variabilidad de los datos reales, lo que puede afectar la generalización del modelo en situaciones del mundo real.

## ¿Cómo funciona el código?

En este proceso, primero se cargan los datos del conjunto Iris y se dividen en conjuntos de entrenamiento y prueba. Luego, los datos se escalan para normalizarlos, lo que garantiza que todas las características tengan la misma escala. A continuación, se entrena un modelo de Máquinas de Vectores de Soporte (SVM) con kernel radial utilizando los datos de entrenamiento, lo que implica ajustar el modelo para encontrar la mejor separación entre las clases de flores en función de sus características. Posteriormente, se evalúa la precisión del modelo tanto en el conjunto de entrenamiento como en el conjunto de prueba para determinar su rendimiento en datos vistos y no vistos. Finalmente, se imprimen los resultados de precisión del modelo en ambos conjuntos, lo que proporciona una medida de su capacidad para clasificar correctamente las flores del conjunto Iris.
