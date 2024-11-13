# Regresion_Multilineal_y_Polinomial

Cierre: miércoles, 13 de noviembre de 2024, 11:00
En el archivo adjunto usted tiene un dataset con variables "x1", "x2" y la varaible "y" a predecir. Su tarea consiste en generar un modelo con el menor error posible para predecir futuros valores de "y", dado algún valor cualquiera de "x1" y "x2".

Cree una jupyter notebook, coloque su nombre y fecha al inicio de la notebook, y complete las siguientes tareas:

1. Cargue el dataset en un dataframe de pandas.
2. Divida el dataset en datos de entrenamiento (x_train) y datos de evaluación (x_test).
3. Genere y entrene un modelo de regresión lineal múltiple con los datos de entrenamiento.
4. Usando el modelo entrenado, calcule los valores predichos (y_test_aprox) para los datos de evaluación (x_test).
5. Con los valores reales (y_test) y valores predichos (y_test_aprox ) calcule el valor de MSE y R^2 para este modelo.
6. Genere y entrene un modelo de regresión polinómica de grado 2. Para esto deberá realizar una transformación polinómica de grado 2 de todos los datos de entrenamiento y evaluación (x_train y x_test).
7. Calcule el valor de MSE y R^2 para este modelo.
8. Genere y entrene un modelo de regresión polinómica de grado 3. Para esto deberá realizar una transformación polinómica de grado 3 de todos los datos de entrenamiento y evaluación (x_train y x_test).
9. Calcule el valor de MSE y R^2 para este modelo.
10. En base a sus resultados de evaluación, indique cuál de los tres modelos es mejor y por qué.
Usted cree que se podría estar generando overfitting o underfitting con su modelo, explique su respuesta.
Con el mejor modelo que obtenga. Prediga cuáles son los valores de y, para los siguientes valores de X1: 1, 10, 100, 1000 y X2: 5, 50, 500, 5000 respectivamente.
Guarde su notebook y súbala el EVA como archivo jupyter notebook sin comprimir.

Rúbrica:

La notebook no debe presentar errores.
Cada tarea debe estar indicada claramente dentro de la notebook.
Su código debe estar bien explicado o comentado.
Las tareas retrasadas tienen un 20% de penalización por día o fracción.
