# Regresión con maquinas de soporte Vectorial

 La regresión con Máquinas de Soporte Vectorial (Support Vector Regression o SVR, por sus siglas en inglés) es una técnica de aprendizaje supervisado utilizada para predecir valores numéricos, en lugar de clasificar datos en categorías. Las Máquinas de Soporte Vectorial (SVM) son conocidas principalmente por su aplicación en problemas de clasificación, pero también pueden adaptarse para problemas de regresión.

Aquí hay una explicación más detallada:

1. Regresión:

- En estadísticas y aprendizaje automático, la regresión implica predecir un valor numérico basado en entradas o características dadas. Por ejemplo, predecir el precio de una casa basándose en características como el número de habitaciones, la ubicación, etc.

1. Máquinas de Soporte Vectorial (SVM):

- Las SVM son un tipo de algoritmo de aprendizaje supervisado que se utiliza comúnmente para problemas de clasificación. La idea central de las SVM es encontrar un hiperplano en un espacio de alta dimensión que mejor separe las diferentes clases de datos. Estas máquinas buscan maximizar el margen entre las clases.

1. Regresión con SVM (SVR):

- En lugar de buscar un hiperplano que separe clases, la regresión con SVM busca un hiperplano que mejor represente la relación entre las variables de entrada y la variable de salida en un espacio de características de alta dimensión.
La SVR se centra en minimizar la diferencia entre las predicciones y los valores reales, permitiendo cierta flexibilidad para tolerar pequeños errores (denominados errores de holgura) dentro de un margen.

1. Kernel Trick:

- Las SVM utilizan el "kernel trick" para mapear los datos a un espacio de características de mayor dimensión, donde es más probable que exista un hiperplano que separe las clases o modele la relación en el caso de regresión.

1. Función de Pérdida y Margen de Tolerancia:

- En SVR, se utiliza una función de pérdida que penaliza las desviaciones de las predicciones con respecto a los valores reales. Además, se introduce un margen de tolerancia (epsilon) que permite cierta flexibilidad en las predicciones.

En resumen, la regresión con Máquinas de Soporte Vectorial es una técnica que utiliza los principios de las SVM para predecir valores numéricos en lugar de clasificar datos en categorías. La flexibilidad de SVR para tolerar pequeños errores y la capacidad de trabajar en espacios de características de alta dimensión hacen que sea útil en diversas aplicaciones de regresión.

## Referencias

- [VECTORES DE SOPORTE REGRESIÓN - TEORÍA](https://www.youtube.com/watch?v=QYkYynoxzBw)
- [¿Cómo funciona SVM?](https://www.youtube.com/watch?v=kl6tyEi5eso)
- [Máquinas de Soporte Vectorial | Cómo funcionan las SVM](https://www.youtube.com/watch?v=XyH8bdv_DSw)
- [Machine Learning - Regresión Máquina de Soporte Vectorial (SVR)](https://www.youtube.com/watch?v=g1yGX_ouHAw)
