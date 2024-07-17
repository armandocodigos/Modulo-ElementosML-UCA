### La actividad trata acerca de entrenar modelos de aprendizaje supervisado.
El objetivo es encontrar un modelo de clasificacion que pueda distinguir entre estados de relajacion y estres en pacientes de un experimento acerca de estres cognitivo y emocional.
- Paso 1: **[Input]** leer tres archivos CSV (separados por coma) y guardarlos en DataFrames de pandas.
- Paso 2: **[Feature engineering]** crear cuatro DataFrames (x_train, x_test, y_train, y_test) que contengan datos de los tres tipos de input. Es decir que tanto en entrenamiento como en prueba se deben tener registros tanto de relax, como de emotional stress y de cognitive stress.
- Paso 3: **[Modeling]** entrenar varios modelos de machine learning, no hay requisito pero se anima a probar tantas combinaciones de hyper-parametros y modelos como usted desee.
- Paso 4: **[Output]** Seleccionar el mejor modelo, calcular su accuracy, mostrar su matriz de confusion y explicar porque usted considera que es el mejor.

Se debe entregar el archivo ipynb (jupiter notebook) en el e-campus para el proximo lunes.

- Punto extra A: utilizar un enfoque de train-validation-test en lugar de train-test.
- Punto extra B: calcular el accuracy por cada clase (3 clases en total).
