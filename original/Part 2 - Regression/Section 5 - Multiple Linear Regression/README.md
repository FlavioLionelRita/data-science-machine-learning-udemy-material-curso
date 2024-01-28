# Restricciones de la regresión lineal múltiple

1. **Linealidad:**

   - La *linealidad* en la regresión lineal implica que la relación entre las variables independientes y la variable dependiente es lineal. Esto significa que un cambio constante en una variable independiente está asociado con un cambio constante en la variable dependiente. Puedes representar esto mediante una línea recta en un gráfico.

2. **Homocedasticidad:**

   - *Homocedasticidad* se refiere a la igualdad de varianzas a lo largo de todos los niveles de las variables independientes. En términos simples, significa que la dispersión de los errores es constante en todos los niveles de las variables predictoras. Si existe Homocedasticidad, los residuos (diferencias entre los valores observados y los predichos) deberían tener una dispersión constante alrededor de la línea de regresión en un gráfico de residuos.

3. **Normalidad multi-variable:**

   - Este término se refiere a la normalidad de los errores en el modelo de regresión lineal. La *normalidad multivariable* implica que los errores siguen una distribución normal conjunta. Aunque la normalidad es importante para inferencias estadísticas más avanzadas, la regresión lineal es bastante robusta a violaciones de la normalidad, especialmente con tamaños de muestra grandes.

4. **Independencia de los errores:**
   - La *independencia de los errores* significa que los errores (las diferencias entre los valores observados y los predichos) no están correlacionados entre sí. En otras palabras, el error asociado con una observación no predice el error de otra observación. La violación de esta suposición puede conducir a sesgos en las estimaciones y a intervalos de confianza incorrectos.

5. **Ausencia de multicolinealidad:**

   - La *ausencia de multicolinealidad* se refiere a la correlación baja entre dos o más variables predictoras en un modelo de regresión. Cuando hay multicolinealidad, se vuelve difícil discernir el efecto individual de cada variable en la variable dependiente. La ausencia de multicolinealidad es importante para tener estimaciones de coeficientes precisas y confiables.

En resumen, para realizar una regresión lineal efectiva, es fundamental que se cumplan estas suposiciones. Sin embargo, en la práctica, es posible que algunas de estas condiciones se vean comprometidas en ciertos casos, y los analistas deben considerar las implicaciones de estas violaciones en la interpretación de los resultados.
