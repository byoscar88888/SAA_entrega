# Título Grande

## ¿Qué es la correlación?

La correlación es una medida que nos dice si dos cosas están relacionadas de alguna manera. Imagina que tienes dos variables, como el tiempo de estudio y la calificación en un examen. Si encuentras una correlación positiva, significa que cuando el tiempo de estudio aumenta, generalmente la calificación también aumenta. Por otro lado, si hay una correlación negativa, significa que cuando una variable aumenta, la otra tiende a disminuir. En resumen, la correlación nos ayuda a entender cómo cambian juntas dos cosas y qué tan fuerte es esa relación. Es una herramienta importante en estadística para comprender patrones y relaciones en los datos.

## Características Principales:

-Acceso fácil a bibliotecas de análisis de datos: Utiliza bibliotecas como Pandas y NumPy.

-Visualización interactiva: Crea gráficos claros y comprensibles con Matplotlib o Seaborn.

-Cálculo de correlación avanzado: Calcula correlaciones de Pearson, Spearman o Kendall según tu necesidad.

-Integración con machine learning: Prepara datos para modelos de machine learning eliminando variables altamente correlacionadas.

<img src="https://www.codetodevs.com/media/posts/mapa-calor-correlaciones-corrcoef-heatmap-pandas.png" alt="Imagen" width="400">


## Ventajas de la correlación

-Identificación de relaciones: La correlación permite identificar relaciones entre variables, lo que ayuda a comprender cómo interactúan diferentes aspectos de los datos.

-Simplicidad: Es una medida simple y fácil de entender que proporciona una descripción cuantitativa de la relación entre dos variables.

-Selección de características: Puede ayudar en la selección de características al identificar aquellas que están altamente correlacionadas con la variable objetivo, lo que puede mejorar la eficacia de los modelos de machine learning.

## Desventajas de la correlación

-No implica causalidad: La correlación no necesariamente indica relación de causa y efecto entre variables.

-Sensibilidad a valores extremos: Valores atípicos pueden distorsionar los resultados de la correlación.

-Dependencia del tipo de datos: No es efectiva para detectar relaciones no lineales o en datos categóricos.

## ¿Cómo funciona el código?

Se genera un DataFrame llamado df que contiene datos simulados sobre edad, altura, peso y puntaje de un grupo de personas, luego se calcula la matriz de correlación entre todas las variables del DataFrame utilizando el método corr() de Pandas, que muestra cómo están relacionadas linealmente las diferentes variables entre sí. Se emplea Seaborn para visualizar la matriz de correlación como un mapa de calor (heatmap), donde cada celda representa el nivel de correlación entre dos variables con colores indicativos de la fuerza y dirección de la correlación. Los valores de correlación se muestran en las celdas con annot=True y fmt=".2f" formatea estos valores con dos decimales. Además, se establece el esquema de color del mapa de calor con cmap='coolwarm' y se ajusta el tamaño de la figura con plt.figure(figsize=(8, 6)), agregando un título al gráfico con plt.title('Matriz de Correlación'). En resumen, este código proporciona una representación visual intuitiva de las relaciones de correlación entre las variables del DataFrame, lo que ayuda a identificar posibles patrones o asociaciones entre ellas.
